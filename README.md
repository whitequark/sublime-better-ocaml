Better OCaml
============

This plugin is a drop-in replacement for the default OCaml package, fixing many of its
shortcomings.

Installation
------------

1. Navigate to the Packages folder (Preferences → Browse Packages...)
2. Unzip [the ZIP archive of Better OCaml](https://github.com/whitequark/sublime-better-ocaml/archive/master.zip). Or, use `git clone git://github.com/whitequark/sublime-better-ocaml`, so that you could use `git pull` to update.

Features
--------

* Fixed highlighting of object-oriented code,
* Added missing keywords and combinations: `inherit!`, `val mutable` and others,
* Added support for keywords added by [Pa_lwt][] syntax extension,
* Added support for locally abstract types (`let foo (type a) (bar : a) = ...`).

[Pa_lwt]: http://ocsigen.org/lwt/api/Pa_lwt
