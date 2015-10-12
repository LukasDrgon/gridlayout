
## [1.0.2] - 2015-10-12

* Make sure the DOM ready event runs only once, in the IE support script.
* Reduce the number of times the grid height setter method runs on the grid cells, by improving the debouncer in the IE support script.
* Fix issues with MS Edge by adding `position:relative` on the `gl-scrollview`.
* Fix failing tests on MS Edge by rounding the numbers returned by `getBoundingClientRect`.

## [1.0.1] - 2015-07-29

* Improvements to the IE-support script for slightly better performance and better support for IE8.
* Fix issues with extra right-side padding on scrollviews, in IE9.
* Website improvements and IE fixes.

## [1.0.0] - 2015-07-28

* Reduce the medium and large breakpoints by 1px, to use 640 and 2014, instead of 641 and 1025.
* Introduce the `.gl-fill` class for grids that take up the entire height of the parent container. Mostly for nested grids that mix grids and other content. Previously, nested grids would take up the entire height of the parent container.
* Improve documentation.

## [0.1.0] - 2015-05-29

* Initial release.
