<!--

@license Apache-2.0

Copyright (c) 2022 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# csch

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Compute the [hyperbolic cosecant][hyperbolic-functions] of a number.



<section class="usage">

## Usage

```javascript
import csch from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-csch@deno/mod.js';
```

#### csch( x )

Computes the [hyperbolic cosecant][hyperbolic-functions] of `x`.

```javascript
var v = csch( 0.0 );
// returns Infinity

v = csch( 2.0 );
// returns ~0.2757

v = csch( -2.0 );
// returns ~-0.2757

v = csch( NaN );
// returns NaN
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
import linspace from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-base-linspace@deno/mod.js';
import csch from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-csch@deno/mod.js';

var x = linspace( -5.0, 5.0, 100 );

var i;
for ( i = 0; i < x.length; i++ ) {
    console.log( csch( x[ i ] ) );
}
```

</section>

<!-- /.examples -->

<!-- C interface documentation. -->



<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/math-base/special/acsch`][@stdlib/math/base/special/acsch]</span><span class="delimiter">: </span><span class="description">compute the hyperbolic arccosecant of a number.</span>
-   <span class="package-name">[`@stdlib/math-base/special/coth`][@stdlib/math/base/special/coth]</span><span class="delimiter">: </span><span class="description">compute the hyperbolic cotangent of a number.</span>
-   <span class="package-name">[`@stdlib/math-base/special/sinh`][@stdlib/math/base/special/sinh]</span><span class="delimiter">: </span><span class="description">compute the hyperbolic sine of a double-precision floating-point number.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/math-base-special-csch.svg
[npm-url]: https://npmjs.org/package/@stdlib/math-base-special-csch

[test-image]: https://github.com/stdlib-js/math-base-special-csch/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/math-base-special-csch/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/math-base-special-csch/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/math-base-special-csch?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/math-base-special-csch.svg
[dependencies-url]: https://david-dm.org/stdlib-js/math-base-special-csch/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/math-base-special-csch/tree/deno
[deno-readme]: https://github.com/stdlib-js/math-base-special-csch/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/math-base-special-csch/tree/umd
[umd-readme]: https://github.com/stdlib-js/math-base-special-csch/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/math-base-special-csch/tree/esm
[esm-readme]: https://github.com/stdlib-js/math-base-special-csch/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/math-base-special-csch/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/math-base-special-csch/main/LICENSE

[hyperbolic-functions]: https://en.wikipedia.org/wiki/Hyperbolic_functions

<!-- <related-links> -->

[@stdlib/math/base/special/acsch]: https://github.com/stdlib-js/math-base-special-acsch/tree/deno

[@stdlib/math/base/special/coth]: https://github.com/stdlib-js/math-base-special-coth/tree/deno

[@stdlib/math/base/special/sinh]: https://github.com/stdlib-js/math-base-special-sinh/tree/deno

<!-- </related-links> -->

</section>

<!-- /.links -->
