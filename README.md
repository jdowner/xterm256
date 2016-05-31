XTERM256
==================================================

This module provides a palette of the colors that are available on an xterm-like
terminal that supports 256 colors, and their RGB equivalents.

I use this utility to take a palette constructed using a tool like
[http://paletton.com paletton], which supports millions of colors, and find the
"best" equivalent for the 256 colors available in the terminal. The "best" match
is found using the abs-max/L1-norm, but any other kind of measure is straight
forward once the colors can be compared numerically.
