# Japan Postal code
JavaScript module for Japan Postal Code.

Forked from https://github.com/ajaxzip3/ajaxzip3.github.io

## How to install
```
npm install japan-postal-code-ts
```

## How to use

```js
var postal_code = require('japan-postal-code');

postal_code.get('1000001', function(address) {
  console.log(address.prefecture); // => "東京都"
  console.log(address.city); // => "千代田区"
  console.log(address.area); // => "千代田"
  console.log(address.street); // => ""
});
```

## LICENSE
MIT License

TODO
- [ ] Need to push code for Typescript
- [ ] Need to make NPM package
