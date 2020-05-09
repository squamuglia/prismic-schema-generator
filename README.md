### Prismic Schema Generator

Being able to generate a schema SDL file from prismic allows you to then generate types for use in your application.

To get started, simply install:

```
yarn global add prismic-schema-generator
```

or

```
npm install -g prismic-schema-generator
```

and run:

```
prismic-schema -r [name of your repository] -o [output file name .gql]
```

#### Notes

Prismic has an annoying habit of typing large sections of responses as JSON. We recommend manually typing this data althought it can be tedious.

If you do generate types off this schema, consider [generating decoders for these types](https://www.npmjs.com/package/decoders)
