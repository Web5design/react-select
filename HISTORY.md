# React-Select

## v0.2.8 / 2014-12-08

* added; `matchPos` option to control whether to match the `start` or `any` position in the string when filtering options (default: `any`)
* added; `matchProp` option to control whether to match the `value`, `label` or `any` property of each option when filtering (default: `any`)

## v0.2.7 / 2014-12-01

* fixed; screen-readers will now read "clear value" instead of "times" for the clear button
* fixed; non-left-click mousedown events aren't blocked by the control


## v0.2.6 / 2014-11-30

* improved; better comparison of changes to [options] in `willReceiveProps`
* fixed; now focuses the first option correctly when in multiselect mode
* fixed; fixed focused option behaviour on value change
* fixed; when filtering, there is always a focused option (#19)
* changed; using ^ in package.json to compare dependencies


## v0.2.5 / 2014-11-20

* fixed; compatibility with case-sensitive file systems

## v0.2.4 / 2014-11-20

* fixed; package.json pointed at the right file

## v0.2.3 / 2014-11-17

* fixed; Updating state correctly when props change
* improved; Build tasks and docs
* added; Working standalone build
* added; Minified dist version
* added; Publised to Bower

## v0.2.2 / 2014-11-15

* fixed; backspace event being incorrectly cancelled

## v0.2.1 / 2014-11-15

* fixed; issue where backspace incorrectly clears the value (#14)

## v0.2.0 / 2014-11-15

* changed; Major rewrite to improve focus handling and internal state management
* added; Support for `multi` prop, enable multiselect mode

## v0.1.1 / 2014-11-03

* added; Support for `onChange` event
* added; `propTypes` are defined by the `Select` component now
* added; `className` property, sets the `className` on the outer `div` element
* fixed; Removed deprecated `React.DOM.x` calls

## v0.1.0 / 2014-11-01

* updated; React to 0.12.0

## v0.0.6 / 2014-10-14

* fixed; Error keeping value when using Async Options
