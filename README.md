Slender (middle)Man
===================
> Who's the tall guy behind you?

![Slenderman illustration](slenderman.jpg "The Slender Man")

A simple template for [Middleman][mdm] opinionated towards simplicity and
cleanness. Useful when prototyping (responsive) web pages.

### Features

#### Prepreocessing

+ [Slim][] *[for html]*
+ [SASS][] *[for css]*
+ [CoffeeScript][] ([jQuery][] ready) *[for js]*

#### Tools
+ [LiveReload][]
+ [Bower][] support *[package management for the web]*
+ [Compass][] or [Bourbon][] (with [Neat][]) *[sass helpers/mixins] + lightweight
  semantic grid*
+ [GitHub Pages][gh-pages] *[deployment/hosting]*
+ [Autoprefixer][] *[add vendor prefixes]*

### Components

+ [HTML5 Boilerplate][h5bp] 4.3.0

#### Via Bower

+ [Modernizr][] 2.6.2
+ [Typeplate][] 1.1.2
+ [PureCSS][] 0.3.0
    + [Normalize.css][] 1.1.2

How to?
-------

### Install

```shell
git clone --depth=1 git://github.com/PaBLoX-CL/slender-man.git ~/.middleman/slender-man
rm -rf ~/.middleman/slender-man/.git # in the likely case you want to remove the history
```

### Use it with MiddleMan

```shell
middleman init my-new-project --template=slender-man
cd my-new-project
bundle install
bower install
```

### Deploy to GitHub Pages (**optional**)

```shell
rake publish
```

More info on the [middleman-gh-pages][neo] repo.

Rationale
---------

I have made this template as simple as possible to rather use it as a sort of
"starting" point, more than a full solution. That's why I made it
delete-friendly and tried to assume the least possible.

Credits
-------

+ [polymatt](https://github.com/polymatt/slimmer/): slimmer MiddleMan Template
+ [shkm](https://github.com/shkm/middleman-neato/): neato MiddleMan Template
+ [polleverywhere](https://github.com/polleverywhere/middleman_bower/): bower
  support
+ [neo](https://github.com/neo/middleman-gh-pages/): deployment method
+ [porada](https://github.com/porada/middleman-autoprefixer/): autoprefixer

Copyright
---------

Copyright (c) 2013 Pablo Olmos de Aguilera Corradini. MIT licensed.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[mdm]: http://middlemanapp.com/
[Slim]: http://slim-lang.com/
[SASS]: http://sass-lang.com/
[CoffeeScript]: http://coffeescript.org/
[jQuery]: http://jquery.com/
[LiveReload]: http://livereload.com/
[Bower]: http://bower.io/
[Compass]: http:://compass-style.org/
[Bourbon]: http://bourbon.io/
[Neat]: http://neat.bourbon.io/
[gh-pages]: http://pages.github.com/
[Autoprefixer]: http://github.com/ai/autoprefixer/
[h5bp]: http://html5boilerplate.com/
[Modernizr]: http://modernizr.com/
[Typeplate]: http://typeplate.com/
[PureCSS]: http://purecss.io/
[Normalize.css]: http://git.io/normalize/
