# Sanitize.stylus

> :nut_and_bolt: [Stylus][stylus] version of [sanitize.css][sanitize]

[![npm][npm-badge]][npm-link]
[![bower][bower-badge]][bower-link]

## Install

**bower**

```bash
$ bower install --save-dev sanitize.stylus
```

**npm**

```bash
$ npm install --save-dev sanitize.stylus
```

## Usage

**Stylus**

Import files in your project using `@import` without the extension below:

```css
@import "/path/to/sanitize"
```

**CSS**

Specify relationships between the current document with [`dist/sanitize.css`][css] from original [sanitize.css][sanitize].

```html
<link rel="stylesheet" href="dist/sanitize.css" type="text/css">
```

## Dcoumentation

> Note: It is written in Japanese :jp:

I am not familier with CSS and I do not want to use things which I do not know how it works so I take notes why they define the rules as reset style on [Wiki](https://github.com/sotayamashita/sanitize.stylus/wiki).

## Contributing

If you have any question or suggestion, please feel free to create issues or pull request. When you create issues or pull request, please read [Contributing](CONTRIBUTING.md) before.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sota Yamashita][me] has waived all copyright and related or neighboring rights to this work. Sanitize.css is dedicated to the [public domain][license] and Stylus port by Sota Yamashita


[stylus]: http://learnboost.github.io/stylus/
[sanitize]: https://github.com/jonathantneal/sanitize.css
[css]: https://github.com/jonathantneal/sanitize.css/blob/master/dist/sanitize.css
[license]: https://github.com/jonathantneal/sanitize.css/blob/master/LICENSE.md
[me]: https://github.com/sotayamashita
[npm-link]: https://www.npmjs.org/package/sanitize.stylus
[npm-badge]: https://img.shields.io/npm/v/sanitize.stylus.svg?style=flat-square
[bower-link]:  http://bower.io/search/?q=sanitize.stylus
[bower-badge]: https://img.shields.io/bower/v/sanitize.stylus.svg?style=flat-square
