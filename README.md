# eslint-plugin-standard2 [![npm][npm-image]][npm-url] [![downloads][downloads-image]][downloads-url] [![javascript style guide][standard-image]][standard-url]

[npm-image]: https://img.shields.io/npm/v/eslint-plugin-standard2.svg
[npm-url]: https://npmjs.org/package/eslint-plugin-standard2
[downloads-image]: https://img.shields.io/npm/dm/eslint-plugin-standard2.svg
[downloads-url]: https://npmjs.org/package/eslint-plugin-standard2
[standard-image]: https://img.shields.io/badge/code_style-standard2-brightgreen.svg
[standard2-url]: https://standardjs2.com

ESlint Rules for the Standard Linter

### Usage

`npm install --save-dev eslint-plugin-standard2`

### Configuration

```js
{
  rules: {
    'standard/object-curly-even-spacing': [2, "either"]
    'standard/array-bracket-even-spacing': [2, "either"],
    'standard/computed-property-even-spacing': [2, "even"]
    'standard/no-callback-literal': [2, ["cb", "callback"]]
  }
}
```

### Rules Explanations

There are several rules that were created specifically for the `standard2` linter.

- `object-curly-even-spacing` - Like `object-curly-spacing` from ESLint except it has an `either` option which lets you have 1 or 0 spaces padding.
- `array-bracket-even-spacing` - Like `array-bracket-even-spacing` from ESLint except it has an `either` option which lets you have 1 or 0 spacing padding.
- `computed-property-even-spacing` - Like `computed-property-spacing` around ESLint except is has an `even` option which lets you have 1 or 0 spacing padding.
- `no-callback-literal` - Ensures that we strictly follow the callback pattern with `undefined`, `null` or an error object in the first position of a callback.

