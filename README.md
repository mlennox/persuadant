# Persuadant

Experiments with responsive layouts and media queries

## Requirements

Uses node 8.9.3 to run the web server that will be accessible at `localhost:8080` after running

```bash
npm start
```

This will run two processes which greatly enhance the development experience:

- [less-watch-compiler](https://www.npmjs.com/package/less-watch-compiler)
- [live-server](https://www.npmjs.com/package/live-server)

The `less-watch-compiler` will recompile the `less` files every time they change. The `live-server` acts as a web server for local static content, and will reload the site whenever the site files change.

## Responsive layout

The point of this little project is to create a CSS-only page layout that will replace the current layout on my [webpusher.ie blog](https://www.webpusher.ie). It is also to refresh and update my CSS knowledge, which although I work with HTML and CSS almost every day, I can experiment a little here.

### Movies

The elements on the page will animate between different screen viewport size breakpoints, mostly for fun, but also because rotating a tablet between portrait and landscape can trigger the reflow and why not make it interesting.

### No JS (except for Nodejs)

The layout is intended to be used on a Jekyll based site, which will be pre-rendered and contain very little javascript.

## Attributions

logo - stars by Made x Made from the Noun Project
