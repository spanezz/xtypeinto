xtypeinto
=========

Pick a string and an X window, and the string is type into the window.

This can be useful to work around things like sites with stupid password fields
that disable pasting, making it possible to use them with password managers
again.

Pass a string to `xtypeinto` as an argument, or as standard input.

`xtypeinto` will show a crosshair to pick a window, and the text will be typed
into that window.

Please make sure that you focus on the right field before running `xtypeinto`,
to make sure things are typed where you need them.

```
$ ./xtypeinto --help
usage: xtypeinto [-h] [--verbose] [--debug] [string]

Type text into a window

positional arguments:
  string         string to type (default: stdin)

optional arguments:
  -h, --help     show this help message and exit
  --verbose, -v  verbose output
  --debug        debug output
```
