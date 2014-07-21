makefontpkg
===========

Name
----

**makefontpkg** - builds a Pacman package from a font file

Synopsis
--------

<pre><code>makefontpkg [-h] [-i] [-s] <var>FILE</var></code></pre>

Description
-----------

Builds a Pacman package from a TrueType or OpenType font file.

Options
-------

  - `-h`, `--help`

    display the help message and quit

  - `-i`, `--install`

    directly install the package

  - `-s`, `--source`

    make a source-only tarball instead of building the package

  - <code><var>FILE</var></code>

    a font file with extension `.ttf` or `.otf`
