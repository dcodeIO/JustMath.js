JustMath.js - 2D Vector Math
============================
An implementation of two dimensional vector math including a rich toolset for vector operations. It's also the math
library behind [eSoccer](http://www.esoccer.me), a cross-platform multiplayer HTML5 game developed at [University of
Applied Sciences Bonn](http://www.h-brs.de).

JustMath
--------
* Augments core Math
* Allows replacement of all methods (e.g. custom implementations of JustMath.sqrt)
* Adds some convenience methods (JustMath.sq, JustMath.cot)

JustMath.Vec2
-------------
* Vector instantiation (new Vec2), cloning (Vec2#clone) and JSON export (Vec2#getXY)
* Direct modification through Vec2#x and Vec2#y, also provides getters (Vec2#getX, Vec2#getY)
* Vector addition (Vec2#add), subtraction (Vec2#sub) and multiplication (Vec2#dot)
* Vector orthogonality (Vec2#ort)
* Vector normalization (Vec2#norm), scaling (Vec2#scale), inversion (Vec2#inv) and magnitude (Vec2#mag, Vec2#magSq) calculation
* Vector-Vector distances (Vec2#dist, Vec2#distSq)
* Vector rotation (Vec2#rot) and direction calculation (Vec2#dir)
* Vector projection (Vec2#project) and rejection (Vec2#reject)
* Vector reflection (Vec2#reflect), also with component-wise scaling (projected and rejected component) (Vec2#reflectAndScale)
* Vector interpolation (Vec2#lerp)
* Vector containment in rectangle (Vec2#inRect)
* [Vector,Vector] determinant calculation (Vec2.det)
* Provides Vector#toString and Vector#equals
* Provides vector operation chaining (e.g. vector.clone().sub(otherVector).norm().project(normalVector)...)
* Small allocation footprint when using Vec2#clone wisely
* Accepts another Vec2 or plain X and Y coordinates as parameters where possible

Features
--------
* [CommonJS](http://www.commonjs.org/) compatible
* [RequireJS](http://requirejs.org/)/AMD compatible
* Shim compatible
* [node.js](http://nodejs.org) compatible, also available via [npm](https://npmjs.org/package/justmath) (npm install justmath)
* [Closure Compiler](https://developers.google.com/closure/compiler/) ADVANCED_OPTIMIZATIONS compatible (fully annotated)
* Fully documented ([jsdoc3](https://github.com/jsdoc3/jsdoc))

Examples & Tests
----------------
* [View](http://htmlpreview.github.com/?https://github.com/dcodeIO/JustMath.js/master/examples/Vec2.html)
* [View source](https://raw.github.com/dcodeIO/JustMath.js/master/examples/Vec2.html)

License
-------
Apache License, Version 2.0 - http://www.apache.org/licenses/LICENSE-2.0.html