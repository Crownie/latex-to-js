latex-to-js
===========

A JavaScript plugin for converting latex equations to js math syntax.

The output is a js math syntax that is only compatible with [mathjs][]

### Usage

Include latex-to-js.js in your html.Then call the **latex\_to\_js();** function with latex string as the argument. The function will return a js math syntax that can be processed by math js or it will throw a syntax error if there is a problem with the latex string.

The converter currently only supports the following latex math functions; fraction,square,nth root,sin, tan and cos

  [mathjs]: http://mathjs.org