# Japan Postal code
Typescript module for Japan Postal Code.

## How to install
```
npm install @40bears/japan-postal-code-ts
```

## How to use

### Import and use
```js
import * as postal_code from "japan-postal-code-ts";

postal_code.get('1000001', function(address) {
  console.log(address.prefecture); // => "東京都"
  console.log(address.city); // => "千代田区"
  console.log(address.area); // => "千代田"
  console.log(address.street); // => ""
});
```

## LICENSE
MIT License
