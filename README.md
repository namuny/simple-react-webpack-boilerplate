Simple React, webpack boilerplate with Ant Design
====================================

This is meant to supplement [this article](https://medium.com/@GeoffMiller/how-to-customize-ant-design-with-react-webpack-the-missing-guide-c6430f2db10f) on how to customize [Ant Design](https://ant.design/docs/react/customize-theme).

## Setup

* `npm install`

* `npm start`

* `go to http://localhost:8080/`

## What's inside

````
$ tree --charset unicode
.
|-- LICENSE
|-- README.md
|-- index.html
|-- package.json
|-- fonts
|-- scripts
|   |-- index.js
|   `-- welcome-message.js
`-- webpack.config.js
````

## Customize Ant Design

Edit the less variables in `scripts/ant-theme-vars.less`. 
A list of available ant theme variables can be found at [https://github.com/ant-design/ant-design/blob/master/components/style/themes/default.less](https://github.com/ant-design/ant-design/blob/master/components/style/themes/default.less)

Fonts have been configured to be served locally instead of the default Alibaba CDN. You can easily move the fonts to your own CDN and point the webpack `themeVariables["@icon-url"]` to your new CDN url.

## Contributors

* Forked from [Yefim Vedernikoff](https://twitter.com/yefim)'s [boilerplate](https://github.com/yefim/simple-react-webpack-boilerplate)
