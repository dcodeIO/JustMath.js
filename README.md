JustMath.js - 2D Vector Math
============================
An implementation of two dimensional vector math including a rich toolset for vector operations. It's also the math
library behind [eSoccer](http://www.esoccer.me), a cross-platform multiplayer HTML5 game developed at University of
Applied Sciences Bonn.

JustMath
--------
* Augments core Math
* Allows replacement of core Math methods
* Adds some convenience methods

JustMath.Vec2
-------------
* Vector instantiation and cloning
* Vector addition, subtraction and multiplication (dot product)
* Vector orthogonality
* Vector normalization, scaling, inversion and magnitude calculation
* Vector-Vector distances
* Vector rotation and direction calculation
* Vector projection and rejection
* Vector reflection, also with component-wise scaling (projected and rejected component)
* Vector interpolation
* Vector containment in rectangle
* [Vector,Vector] determinant calculation
* Provides vector operation chaining
* Small allocation footprint when using clone() wisely

Features
--------
* [CommonJS](http://www.commonjs.org/) compatible
* [RequireJS](http://requirejs.org/)/AMD compatible
* Shim compatible
* [node.js](http://nodejs.org) compatible, also available via [npm](https://npmjs.org/package/justmath) (npm install justmath)
* [Closure Compiler](https://developers.google.com/closure/compiler/) ADVANCED_OPTIMIZATIONS compatible (fully annotated)

Examples & Tests
----------------
* [View](http://htmlpreview.github.com/?https://github.com/dcodeIO/JustMath.js/master/examples/Vec2.html)
* [View source](https://raw.github.com/dcodeIO/JustMath.js/master/examples/Vec2.html)

License
-------
Apache License, Version 2.0 - http://www.apache.org/licenses/LICENSE-2.0.html