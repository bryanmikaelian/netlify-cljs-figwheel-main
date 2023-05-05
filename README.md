# netlify-cljs-figwheel


[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/bryanmikaelian/netlify-cljs-figwheel)

[![Netlify Status](https://api.netlify.com/api/v1/badges/52e37e79-0eac-45e1-8477-d07f490f90f6/deploy-status)](https://app.netlify.com/sites/fabulous-sherbet-ca4ef9/deploys)

This a lightweight template that lets you deploy a `figwheel-main`-based ClojureScript project on Netlify.

# Commands

Two base builds have been provided:

## dev
This should be used for local development

```sh
clj -M -m figwheel.main -b dev -r
```

## prod
This should be used for production developments
```sh
clj -m figwheel.main -O advanced -bo prod
sh

## Interested in using `shadow-cljs`?

Checkout https://github.com/bryanmikaelian/netlify-cljs-shadowcljs
