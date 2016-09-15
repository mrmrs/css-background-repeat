# css-background-repeat 1.0.5

Css module of single purpose classes for background repeat

#### Stats

261 | 24 | 24
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-background-repeat
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-background-repeat
```

ssh:
```
git clone git@github.com:tachyons-css/css-background-repeat.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-background-repeat";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-background-repeat@1.0.5/css/css-background-repeat.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-background-repeat">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Media Queries */
/*
   BACKGROUND REPEAT
*/
.bg-norep { background-repeat: no-repeat; }
.bg-x { background-repeat: repeat-x; }
.bg-y { background-repeat: repeat-y; }
.bg-rep { background-repeat: repeat; }
.bg-spc { background-repeat: space; }
.bg-rnd { background-repeat: round; }
@media (min-width: 48em) {
 .bg-norep-ns { background-repeat: no-repeat; }
 .bg-x-ns { background-repeat: repeat-x; }
 .bg-y-ns { background-repeat: repeat-y; }
 .bg-rep-ns { background-repeat: repeat; }
 .bg-spc-ns { background-repeat: space; }
 .bg-rnd-ns { background-repeat: round; }
}
@media (min-width: 48em) and (max-width: 64em) {
 .bg-norep-m { background-repeat: no-repeat; }
 .bg-x-m { background-repeat: repeat-x; }
 .bg-y-m { background-repeat: repeat-y; }
 .bg-rep-m { background-repeat: repeat; }
 .bg-spc-m { background-repeat: space; }
 .bg-rnd-m { background-repeat: round; }
}
@media (min-width: 64em) {
 .bg-norep-l { background-repeat: no-repeat; }
 .bg-x-l { background-repeat: repeat-x; }
 .bg-y-l { background-repeat: repeat-y; }
 .bg-rep-l { background-repeat: repeat; }
 .bg-spc-l { background-repeat: space; }
 .bg-rnd-l { background-repeat: round; }
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

