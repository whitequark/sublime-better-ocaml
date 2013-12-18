Better OCaml
============

This plugin is a drop-in replacement for the default OCaml package, fixing many of its
shortcomings.

Installation
------------

1. Install Package Control. http://wbond.net/sublime_packages/package_control
2. Install Better OCaml
  1. Preferences | Package Control | Package Control: Install Package
  2. Choose OCaml

Features
--------

* Fixed highlighting of object-oriented code,
* Added missing keywords and combinations: `inherit!`, `val mutable` and others,
* Added support for keywords added by [Pa_lwt][] syntax extension,
* Added support for locally abstract types (`let foo (type a) (bar : a) = ...`).

[Pa_lwt]: http://ocsigen.org/lwt/api/Pa_lwt
