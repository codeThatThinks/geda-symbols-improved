# geda-symbols-improved

A better symbol library for gEDA. Smaller, more consistent, and more readable. This is intended to be a complete replacement of the library included with gEDA.

![Screenshot](screenshot.svg)

## Installation

Copy the `sym-improved` folder to `/usr/share/gEDA/`. Then modify your `~/.gEDA/gafrc` add add the following lines at the end:

```
(reset-component-library)
(component-library-search "/usr/share/gEDA/sym-improved/")
```

Also add the following lines to `~/.gEDA/gschemrc` for an improved user experience:

```
(snap-size 50)
(text-size 6)
(pin-style "thick")
(line-style "thick")
```

### Titleblock

To use the letter-sized titleblock as default, add the following to `~/.gEDA/gschemrc`:

```
(define default-titleblock "title-bordered-letter.sym")
```

## License

These symbols are released under [Creative Commons Zero (CC0)](http://creativecommons.org/publicdomain/zero/1.0/).

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
