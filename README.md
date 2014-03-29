d3-elements
===========

See the [component page](http://polymerlabs.github.io/d3-elements) for more information.

d3-import
=========

Import files are a new invention, so libraries like [`d3`](http://bugzu.github.io/reD3/) do not yet provide them.

`d3-import` is an intermediary that provides an import file for the `d3` component. 
`d3-import` depends on `d3`.

Components that want to use `d3` should depend on `d3-element` and import `d3-import` to be safe from library duplication. 
Such components need not use Polymer or `d3-element`, but we put the import and the element in one package for convenience.
