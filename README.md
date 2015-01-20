TUM-Script
==========

Logos of the [Technische Universität München](http://www.tum.de/) in
hand-written PostScript. Why? Because I can!


Viewing
-------

You'll want to use [GhostScript](http://www.ghostscript.com/) since GS supports
more PostScript features and renders better than other libraries like
[poppler](http://poppler.freedesktop.org/). GS is bundled with just about every
desktop Linux distribution and can be installed from the repositories in ever
other.

You can also instruct GhostScript to convert the PostScript sources to PDF
files which can be displayed by just about every PDF viewer and program that
handles PDF:

```sh
gs -sDEVICE=pdfwrite -sOutputFile=output.tum.pdf -dBATCH -dNOPAUSE input.tum.ps
```

License
-------

The files are [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)
licensed, so they are as free as possible from my side.
