# CSS SQUARES

  Mobile-first classes for css-squares.
  Set the desired css-squares on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-squares
```
or download the css on github and include in your project.

## File Size


## The Code
```
.sq1 { width: 1rem;  height: 1rem; }
.sq2 { width: 2rem;  height: 2rem; }
.sq3 { width: 4rem;  height: 4rem; }
.sq4 { width: 8rem;  height: 8rem; }
.sq5 { width: 16rem; height: 16rem; }
.sq6 { width: 32rem; height: 32rem; }
.sq7 { width: 48rem; height: 48rem; }
.sq8 { width: 64rem; height: 64rem; }
.sq9 { width: 96rem; height: 96rem; }

@media screen and (min-width: 48em) {
  .sq1-ns { width: 1rem;  height: 1rem; }
  .sq2-ns { width: 2rem;  height: 2rem; }
  .sq3-ns { width: 4rem;  height: 4rem; }
  .sq4-ns { width: 8rem;  height: 8rem; }
  .sq5-ns { width: 16rem; height: 16rem; }
  .sq6-ns { width: 32rem; height: 32rem; }
  .sq7-ns { width: 48rem; height: 48rem; }
  .sq8-ns { width: 64rem; height: 64rem; }
  .sq9-ns { width: 96rem; height: 96rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .sq1-m { width: 1rem;  height: 1rem; }
  .sq2-m { width: 2rem;  height: 2rem; }
  .sq3-m { width: 4rem;  height: 4rem; }
  .sq4-m { width: 8rem;  height: 8rem; }
  .sq5-m { width: 16rem; height: 16rem; }
  .sq6-m { width: 32rem; height: 32rem; }
  .sq7-m { width: 48rem; height: 48rem; }
  .sq8-m { width: 64rem; height: 64rem; }
  .sq9-m { width: 96rem; height: 96rem; }
}

@media screen and (min-width: 64em)  {
  .sq1-l { width: 1rem;  height: 1rem; }
  .sq2-l { width: 2rem;  height: 2rem; }
  .sq3-l { width: 4rem;  height: 4rem; }
  .sq4-l { width: 8rem;  height: 8rem; }
  .sq5-l { width: 16rem; height: 16rem; }
  .sq6-l { width: 32rem; height: 32rem; }
  .sq7-l { width: 48rem; height: 48rem; }
  .sq8-l { width: 64rem; height: 64rem; }
  .sq9-l { width: 96rem; height: 96rem; }
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

