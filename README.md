# w-package-json [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![Version](https://img.shields.io/npm/v/w-package-json.svg)](https://www.npmjs.com/package/w-package-json) [![Downloads](https://img.shields.io/npm/dt/w-package-json.svg)](https://www.npmjs.com/package/w-package-json) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> Write package.json files.

## Example

```js
const writePack = require("w-package-json");

writePack(__dirname, {
    name: "hello-world"
  , version: "1.0.0"
}, function (err, pack) {
    console.log(err || pack);
});
```

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Related

 - [`r-package-json`](https://github.com/IonicaBizau/r-package-json)–Read package.json files.

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2016#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md