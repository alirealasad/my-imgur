"# my-imgur"

npm registry:-https://www.npmjs.com/package/my-imgur

## Module Usage

### Installation
Install the project dependencies.You can use npm or yarn(recommended) for dependency management。

```bash
## npm
npm i my-imgur

```

### Usage

You can through this website to get your project's client id.

https://api.imgur.com/oauth2/addclient

```js
// Requiring the module
const imgur = require('my-imgur');

// intilize client id
imgur.setClientId('Your Client Id');

// uploading image file
imgur.uploadImgur(yourFile).then((result) => {
  console.log(result);
});

```

## License
#### MIT

[npm-image]: https://img.shields.io/badge/npm-v1.1.0-blue.svg
[npm-url]: https://www.npmjs.com/package/my-imgur
