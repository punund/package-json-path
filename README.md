
# package-json-path

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Version](https://img.shields.io/npm/v/package-json-path.svg)](https://www.npmjs.com/package/package-json-path) [![Downloads](https://img.shields.io/npm/dt/package-json-path.svg)](https://www.npmjs.com/package/package-json-path)

> Get the package.json path in a specific directory.

## :cloud: Installation

```sh
$ npm i --save package-json-path
```


## :clipboard: Example



```js
const packPath = require("package-json-path");

console.log(packPath("~/path/to/my/module"));
// => /home/ionicabizau/path/to/my/module/package.json

console.log(packPath("relative/path/to/module"));
// => /home/ionicabizau/Documents/.../relative/path/to/module/package.json
```

## :memo: Documentation


### `packageJsonPath(dir)`
Finds the absolute path to the `package.json` path.

#### Params
- **String** `dir`: The path to the directory.

#### Return
- **String** The absolute path to the `package.json` file.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:


## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`bloggify-plugin-class`](https://github.com/IonicaBizau/bloggify-plugin-class#readme)—A library for managing plugin objects.
 - [`made-in-brazil`](https://github.com/IonicaBizau/made-in-brazil#readme)—A list of neat projects made in Brazil.
 - [`made-in-india`](https://github.com/IonicaBizau/made-in-india#readme)—A list of neat projects made in India.
 - [`made-in-romania`](https://github.com/IonicaBizau/made-in-romania#readme)—A list of cool projects made in Romania.
 - [`np-init`](https://github.com/IonicaBizau/np-init#readme)—Easily start a npm package from scratch.
 - [`packy`](https://github.com/IonicaBizau/packy#readme)—Set default fields in your package.json files.
 - [`r-package-json`](https://github.com/IonicaBizau/r-package-json#readme)—Read package.json files.
 - [`ship-release`](https://github.com/IonicaBizau/ship-release#readme)—Publish new versions on GitHub and npm with ease.
 - [`w-package-json`](https://github.com/IonicaBizau/w-package-json#readme)—Write package.json files.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2016#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
