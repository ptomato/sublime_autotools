# Contributing to Sublime Autotools #

This package is considered stable, with occasional bug fixes.
If you find a bug, a pull request is both greatly appreciated and the
fastest way to get the bug fixed.

## Testing your changes ##

The best way to make changes to this package and test them, is to make a
link to your Git checkout in the Packages directory in your Sublime Text
configuration dir.
That way, the files in your checkout directory will override the ones in
the installed package.
Read more about how this works in "Overriding Files From a Zipped
Package" on https://www.sublimetext.com/docs/3/packages.html.

For example, on macOS, make the link like this:
```sh
ln -s ~/path/to/sublime_autotools ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/Autotools
```

## Creating a pull request ##

To create a pull request, make sure you have updated all the necessary
files.
If you change one of the `.JSON-tmLanguage` files, you should regenerate
and commit the `.tmLanguage` PList file as well.
The best way to do this is to install the "PackageDev" package in
Sublime Text.
When you have changed the `.JSON-tmLanguage` file, use PackageDev to
regenerate the other one.
(Shift+Ctrl+P, "PackageDev: Convert (YAML, JSON, PList) to...")
