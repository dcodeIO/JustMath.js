JustMath.js
===========
An implementation of two dimensional vector math including a rich toolset for vector operations.
It's also the math library behind [eSoccer](http://www.esoccer.me).

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

Loading
-------
* CommonJS compatible
* RequireJS/AMD compatible
* Shim compatible

Examples & Tests
----------------
* [View](http://htmlpreview.github.com/?https://github.com/dcodeIO/JustMath.js/master/examples/Vec2.html)
* [View source](https://raw.github.com/dcodeIO/JustMath.js/master/examples/Vec2.html)

License
-------
Apache License, Version 2.0 - http://www.apache.org/licenses/LICENSE-2.0.html