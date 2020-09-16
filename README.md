# @modyqyw/stylelint-config-less

A Stylelint shareable config for less. Also support miniprograms.

## Usage

- Install the config.

```sh
npm i stylelint@~13.7.0 @modyqyw/stylelint-config-less@~1.1.0 -D
```

For yarn, run scripts below.

```sh
yarn add stylelint@~13.7.0 @modyqyw/stylelint-config-less@~1.1.0 -D
```

- Set up.

```js
// stylelint.config.js
module.exports = {
  extends: ["@modyqyw/stylelint-config-less"],
};
```

## VSCode

- Install plugins.
  - [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
- Set up `Settings.json`. Then `F1 => File: Save`.

```json
{
  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "files.associations": {
    "*.wxml": "html",
    "*.wxs": "javascript",
    "*.wxss": "css",
    "*.axml": "html",
    "*.sjs": "javascript",
    "*.acss": "css",
    "*.swan": "html",
    "*.ttml": "html",
    "*.ttss": "css",
    "*.jxml": "html",
    "*.jxss": "css",
    "*.wpy": "vue",
    "*.nvue": "vue",
    "*.ux": "vue"
  }
}
```

## More Config

- [@modyqyw/stylelint-config-css](https://github.com/MillCloud/stylelint-config-css)
- [@modyqyw/stylelint-config-scss](https://github.com/MillCloud/stylelint-config-scss)

## License

[MIT](./LICENSE)

Copyright (c) 2020-present MillCloud
