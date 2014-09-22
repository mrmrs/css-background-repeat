# CSS BACKGROUND REPEAT

  Mobile-first classes for css-background-repeat.
  Set the desired css-background-repeat on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-background-repeat
```
View on [npm](https://www.npmjs.org/package/css-background-repeat)


## File Size

1.3K background-repeat.css
980B background-repeat.min.css 
218B minified and gzipped

## The Code
```
  .bg-norep {  background-repeat: no-repeat; }
  .bg-x {      background-repeat: repeat-x; }
  .bg-y {      background-repeat: repeat-y; }
  .bg-rep {    background-repeat: repeat; }
  .bg-spc {    background-repeat: space; }
  .bg-rnd {    background-repeat: round; }

@media screen and (min-width: 48em) {
  .bg-norep-ns {  background-repeat: no-repeat; }
  .bg-x-ns {      background-repeat: repeat-x; }
  .bg-y-ns {      background-repeat: repeat-y; }
  .bg-rep-ns {    background-repeat: repeat; }
  .bg-spc-ns {    background-repeat: space; }
  .bg-rnd-ns {    background-repeat: round; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .bg-norep-m {  background-repeat: no-repeat; }
  .bg-x-m {      background-repeat: repeat-x; }
  .bg-y-m {      background-repeat: repeat-y; }
  .bg-rep-m {    background-repeat: repeat; }
  .bg-spc-m {    background-repeat: space; }
  .bg-rnd-m {    background-repeat: round; }
}

@media screen and (min-width: 64em)  {
  .bg-norep-l {  background-repeat: no-repeat; }
  .bg-x-l {      background-repeat: repeat-x; }
  .bg-y-l {      background-repeat: repeat-y; }
  .bg-rep-l {    background-repeat: repeat; }
  .bg-spc-l {    background-repeat: space; }
  .bg-rnd-l {    background-repeat: round; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

