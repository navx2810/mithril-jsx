# mithril-jsx
A poi.js preset for Mithril and JSX.

## Uses

* babel-preset-es2015: ^6.24.1
* babel-plugin-transform-class-properties: ^6.24.1
* babel-plugin-transform-decorators-legacy: ^1.3.4
* babel-plugin-transform-react-jsx:^6.24.1

## Instructions
```js
// poi.config.js
module.exports = {
    presets: [
        require('poi-preset-mithril-jsx')()
    ]
}
```
