Intersection Observer Recipes
=============================


This is an attempt to catalog various popular UI patterns in the browser
that traditionally use a scroll event, and show how they can be
rewritten to use Intersection Observer.


Big caveat is that the example neither show the most efficient way nor
are feature complete. They show the usecases of IntersectionObserver API
in the quickest fashion.


Usage
=====


1. Clone this repository
2. Open each file in a browser. All the JS and CSS is inlined, so you
   don't need any server or external dependencies.


Compatibility
=============

The examples use semi-modern features (arrow functions, `const`, `let`
being the major ones), so please use a modern browser. You can see the
support matrix for the features here:


1. IntersectionObserver complete: https://caniuse.com/#feat=intersectionobserver
2. Flexbox: https://caniuse.com/#feat=flexbox
3. ES6 features: http://kangax.github.io/compat-table/es6/


Coming up next
--------------

1. "Sticky" positioning effect for elements.
