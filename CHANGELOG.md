## 1.1.2 / 4 November 2022

* Widen the `Endpoint` type in the typings to accept any primitive or object
  with a valueOf method [#15]. Thanks, [@petercpwong]!

## 1.1.1 / 14 October 2021

* Depend on stRange.js types [#14]. Thanks, [@bdbaraban]!

## 1.1.0 / 28 March 2019

* Bundle TypeScript definitions [#10]. Thanks, [@cliedeman]!

## 1.0.1 / 31 January 2019

* Bump dependencies. This notably silences a `npm audit` warning [#7].
* Drop support for Node versions 4.x and earlier.

## 1.0.0 / 24 July 2016

* Subclass returned `Range` objects from [js-strange] objects to provide
  useful methods for range manipulation and inspection.

## 0.1.2 / 24 April 2015

* Explicitly license under MIT.

## 0.1.1 / 28 July 2014

* Loosen range validity checking.

## 0.1.0 / 7 April 2014

* Support coercing range objects into queries.

## 0.0.1 / 28 March 2014

* Initial release.
* Support returning range object from queries.

[@bdbaraban]: https://github.com/bdbaraban
[@cliedeman]: https://github.com/cliedeman
[@petercpwong]: https://github.com/petercpwong
[js-strange]: https://github.com/moll/js-strange
[#7]: https://github.com/WhoopInc/node-pg-range/issues/7
[#10]: https://github.com/WhoopInc/node-pg-range/issues/10
[#14]: https://github.com/WhoopInc/node-pg-range/issues/14
[#15]: https://github.com/WhoopInc/node-pg-range/pull/15
