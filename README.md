Sublime Autotools
=================

**Autotools syntax highlighting for Sublime Text**

This package includes syntax highlighting for Autoconf M4 and Automake files.

`Makefile.am` is normally Automake code, but Sublime Text highlights it
as Makefile code by default.
If you want the Automake definition in this package to override the
default syntax highlighting for `Makefile.am`, you can choose **View** →
**Syntax** → **Open all with current extension as...** → **Autotools** →
**Automake**.

Note: For Autoconf M4 macros, the arguments may need to be highlighted in
several different ways; some are shell code, some are plain text, and a few
are C code. There are definitions for the builtin ones, but custom macros
may not be highlighted correctly.
