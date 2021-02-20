# Rhys' Blog

This repo is for my [(rhys-the-davies)](https://rhys-the-davies.com) [blog site](https://blog.rhys-the-davies.com). The theme is a port of Ghost's default theme [Casper v1](https://github.com/tryghost/casper) for Jekyll by [Rosario called Kasper](https://github.com/rosario/kasper)

Feel free to fork, change, modify and re-use it.

## Installation

    git clone https://github.com/rhys-the-davies/myblog
    cd kasper
    gem install jekyll
    gem install jekyll-paginate

## Change _config.yml

Change the following settings in _config.yaml. Most likely you want the `baseurl: ""`

```
baseurl: ""
domain_name: "yourblog-domain.com"
```

## How to use it

Build page and start local web server

    jekyll serve

Build page into `_site` folder

    jekyll build

## Kasper theme includes

* Pagination
* Rss
* Google Analytics Tracking code
* Code Syntax Highlight
* Author's profile with picture
* Disqus comments

## Copyright & License

Copyright (C) 2013 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
