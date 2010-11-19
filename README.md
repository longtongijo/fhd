Clostache
=========

[{{ mustache }}](http://mustache.github.com) for Clojure.

Although it already works with simple templates, this is still work in
progress. See the TODO file for not yet implemented features.

[![Flattr this](http://api.flattr.com/button/button-compact-static-100x17.png "Flattr this")](http://flattr.com/thing/73492/Clostache)

Installation
------------

The easiest way to install it is to use [cljr](https://github.com/liebke/cljr) from [Clojars](http://clojars.org)

  clrj install com.github.fhd.clostache/clostache

Usage
-----

The easiest way to use Clostache in your project is via
[Clojars](http://clojars.org/com.github.fhd.clostache/clostache).

This is how you can use Clostache from the REPL:

	=> (use 'clostache.parser)
	=> (render "Hello, {{name}}!" {:name "Felix"})
	"Hello, Felix!"

See the test cases for more sophisticated examples.

License
-------

Copyright (C) 2010 Felix H. Dahlke

This library is free software; you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as
published by the Free Software Foundation; either version 2.1 of the
License, or (at your option) any later version.

This library is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; see the file COPYING. If not, write
to the Free Software Foundation, Inc., 51 Franklin Street, Fifth
Floor, Boston, MA 02110-1301 USA
