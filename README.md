# netlify-cljs-figwheel-main


[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/bryanmikaelian/netlify-cljs-figwheel)

This a lightweight template that lets you deploy a `figwheel-main`-based ClojureScript project on Netlify.

A demo of this site can be found at https://cljs-demo-figwheel-main.netlify.app/

## Builds

Two base builds have been provided:

### dev
This should be used for local development

```sh
clj -M -m figwheel.main -b dev -r
```

### prod
This should be used for production developments
```sh
clj -m figwheel.main -O advanced -bo prod
sh
```

## Interested in using `shadow-cljs`?

Checkout https://github.com/bryanmikaelian/netlify-cljs-shadowcljs
