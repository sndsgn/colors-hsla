# COLORS

## Better colors for the web.

View the project page at [http://clrs.cc](http://clrs.cc "Colors: Better colors for the web.")

## What is this?

A simple color palette for the web. Let's be honest, out of the box, the color strings that css provides aren't... the tops.
This is a set of sass/less/stylus/css variables and css classes that can help fix that with just 647B of minified and gzipped css.

(Uncompressed is just 888B)

colors.css provides utilities to apply backgrounds, text-color, border colors for both html and svg elements. 

# Example
```
.blue {         color: $blue; }
.bg-blue {      backgroundcolor: $blue; }
.border--blue { border-color: $blue; }
.fill-blue {    fill: $blue; }
.stroke-blue {  stroke: $blue; }
```

## Install colors.css

You can get the code a few different ways

Download a zip from this page

Clone / fork the repo through git
```bash
git clone git@github.com:sndsgn/colors-hsla.git
```

### Using the css
Simply copy colors.css to your css directory and include the file like so in the head of your html document

```html
<link rel="stylesheet" href="css/colors-hsla.css">
```

# Author
[SNDSGN](http://www.sndsgn.com " Robert Forloine - HTML, CSS, JavaScript designed to render smoothly and quickly")

# License

The MIT License (MIT)

Copyright (c) 2014 @sndsgns
Based off of clrs.cc by @mrmrs_ 

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

