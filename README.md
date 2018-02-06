# u-mandelbrot.el

## Philosophy:

The following ideas have been focussed during the development of this
package (`u-mandelbrot.el`).

* It is intended as a small contribution to support the
  Neo-Post-Retro-Programming(TM) Movement.

* It shall give another demonstration of the fact that Emacs not only
  is The One True Editor, but also The Universal User Interface.

* It shall demonstrate that there are more ways to waste your time than
  you might have thought.

* It shall remind you of the good old days when your screen had a
  resolution of 160 x 120 pixels and everything was much better. 

## Installation Instructions:

In order to use this package, load this file and say `M-x u-mandelbrot
RET`. For performance reasons you might want to consider byte-compiling
this file. 
If you have tried that, and you should feel like using this package
ever again, you might want to place this file somewhere in your
load-path and put the following in your Emacs startup file (~/.emacs)

    (autoload 'u-mandelbrot "u-mandelbrot" "A simple fractal browser" t)

## Usage:

Just call `u-mandelbrot` and follow the instructions. Please be patient
-- it might take a while...

## Commentary / Disclaimer:

This is the result of weekend work. Don't expect too much. It does not
make use of any fancy tricks. It just applies the `$`z \rightarrow z^2 +
z_0`$` algorithm in a brute force way.

The "ascii color-table" is quite poor. It should be enlarged.

This package has been tested on Emacs 20.7.1 and XEmacs 21.1.10.
Apparently it runs faster with XEmacs... (!?)

(X)Emacs versions prior to these will never be supported.

## History:

* 1.0: Initial release

