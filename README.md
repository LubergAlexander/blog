# Static blog on metalsmith
## Description
- ./src/layouts contains handlebars layouts for index and post page
- ./src/posts contains markdown files with posts

Metalsmith will compile markdown to html with the given layout.
CSS is processed with PostCSS.


## Installation

```
npm install
```

## Serve & watch locally
It will start a webserver on localhost:8080 with livereloading (Chrome extension is required)

```
npm start
```

## Clean
Remove everything in build folder to start from scratch

```
npm run clean
```

## Publish
TODO

