# css-squares 0.0.6

Css module of single purpose classes for squares

#### Stats

293 | 36 | 72
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-squares
```

#### With Git

```
git clone https://github.com/tachyons-css/css-squares
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-squares";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-squares">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   SQUARES
*/
.sq1 { width: 1rem; height: 1rem; }
.sq2 { width: 2rem; height: 2rem; }
.sq3 { width: 4rem; height: 4rem; }
.sq4 { width: 8rem; height: 8rem; }
.sq5 { width: 16rem; height: 16rem; }
.sq6 { width: 32rem; height: 32rem; }
.sq7 { width: 48rem; height: 48rem; }
.sq8 { width: 64rem; height: 64rem; }
.sq9 { width: 96rem; height: 96rem; }
@media screen and (min-width: 48em) {
 .sq1-ns { width: 1rem; height: 1rem; }
 .sq2-ns { width: 2rem; height: 2rem; }
 .sq3-ns { width: 4rem; height: 4rem; }
 .sq4-ns { width: 8rem; height: 8rem; }
 .sq5-ns { width: 16rem; height: 16rem; }
 .sq6-ns { width: 32rem; height: 32rem; }
 .sq7-ns { width: 48rem; height: 48rem; }
 .sq8-ns { width: 64rem; height: 64rem; }
 .sq9-ns { width: 96rem; height: 96rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .sq1-m { width: 1rem; height: 1rem; }
 .sq2-m { width: 2rem; height: 2rem; }
 .sq3-m { width: 4rem; height: 4rem; }
 .sq4-m { width: 8rem; height: 8rem; }
 .sq5-m { width: 16rem; height: 16rem; }
 .sq6-m { width: 32rem; height: 32rem; }
 .sq7-m { width: 48rem; height: 48rem; }
 .sq8-m { width: 64rem; height: 64rem; }
 .sq9-m { width: 96rem; height: 96rem; }
}
@media screen and (min-width: 64em) {
 .sq1-l { width: 1rem; height: 1rem; }
 .sq2-l { width: 2rem; height: 2rem; }
 .sq3-l { width: 4rem; height: 4rem; }
 .sq4-l { width: 8rem; height: 8rem; }
 .sq5-l { width: 16rem; height: 16rem; }
 .sq6-l { width: 32rem; height: 32rem; }
 .sq7-l { width: 48rem; height: 48rem; }
 .sq8-l { width: 64rem; height: 64rem; }
 .sq9-l { width: 96rem; height: 96rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
