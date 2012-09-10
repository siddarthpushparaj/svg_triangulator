svg_triangulator
================
svg_triangulator is a small node.js cli script that takes an SVG file as input and outputs triangulated coordinates for each path suitable for rendering in OpenGL with GL_TRIANGLES

Installation
============
* clone the repository (git@github.com:robmerrell/svg_triangulator.git)
* `npm install` to install dependencies

Using
=====
Just point the svg_triangulator script at an SVG file and watch the magic work. --help will give you available output and point options

What it lacks
=============
svg_triangulator is a quick script I wrote to test out some 2d polygon rendering ideas that I had. It is very likely to crash with any sophisticated SVG. At the moment it only acts on the M,m,L,l operations of a path. Since a closed path is assumed only one move operation within the path data is used.

License
=======
svg_triangulator is licensed under the MIT license. Do what you will with it.

Copyright (c) 2012 Rob Merrell

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