# {{ name }}

> {{ description }}

## Build Setup

``` bash
# install dependencies
yarn install

# serve with hot reload at localhost:8080
yarn run dev

# build for production with minification
yarn run build

# build for production and view the bundle analyzer report
yarn run build --report
{{#unit}}

# run unit tests
yarn run unit
{{/unit}}
{{#e2e}}

# run e2e tests
yarn run e2e
{{/e2e}}
{{#if_or unit e2e}}

# run all tests
yarn test
{{/if_or}}
```

## About the boilerplate

This repository uses the [codeams/vuepack](http://github.com/codeams/vuepack) template.

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
