Slender (middle)Man
===================
> Who's the tall guy behind you?

![Slenderman illustration](slenderman.jpg "The Slender Man")

A simple template for [Middleman][mdm] opinionated towards simplicity and
cleanness.

### Features

+ [Slim][]
+ [Stylus][] (and [nib][])
+ [Coffeescript][] ([jQuery][] ready)
+ [LiveReload][]
+ [Bower][] support
+ Easy deployment as a static app to [Heroku][] for review and testing
  (shameless ripoff from [middleman-combined][])

### Components

+ [HTML5 Boilerplate][h5bp] 4.3.0

#### Via Bower

+ [Modernizr][] 2.6.2
+ [PureCSS][] 0.3.0
    + [Normalize.css][] 1.1.2

How to?
-------

### Install

```shell
git clone git://github.com/PaBLoX-CL/slender-middle-man.git ~/.middleman/slender-middle-man
```

### Use it with MiddleMan

```shell
middleman init my-new-project --template=slender-middle-man
cd my-new-project
bundle install
npm install
bower install
```

### Push to Heroku (**optional**)

```shell
heroku create && git push heroku master
```

Rationale
---------

I have made this template as simple as possible to rather use it as a sort of
"starting" point, more than a full solution. That's why I made it
delete-friendly.

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
[Stylus]: http://learnboost.github.io/stylus/
[nib]: http://visionmedia.github.io/nib/
[Coffeescript]: http://coffeescript.org/
[jQuery]: http://jquery.com/
[LiveReload]: http://livereload.com/
[Bower]: http://bower.io/
[middleman-combined]: https://github.com/nathanlong/middleman-combined/
[h5bp]: http://html5boilerplate.com/
[Normalize.css]: http://git.io/normalize/
[Modernizr]: http://modernizr.com/
[PureCSS]: http://purecss.io/

