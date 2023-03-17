# pyenv-legacy

[![Build Status](https://travis-ci.com/0q2/pyenv-legacy.svg?branch=master)](https://travis-ci.com/0q2/pyenv-legacy)

pyenv-legacy is a [pyenv](https://github.com/pyenv/pyenv) plugin
that provides a `pyenv legacy` command to help diagnose python projects that lack specified versioning.

## Installation

### Installing as a pyenv plugin

Installing pyenv-legacy as a pyenv plugin will give you access to the
`pyenv legacy` command.

First make sure ['jq'](https://stedolan.github.io/jq/) is installed and in your path. Then:

    $ git clone https://github.com/0q2/pyenv-legacy.git $(pyenv root)/plugins/pyenv-legacy

## Usage

To select from python versions that were supported at the time of the last commit of the current directory's git branch, just type `pyenv legacy`.

    $ pyenv legacy

### License

(The MIT License)

* Copyright (c) 2023 0q2

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
