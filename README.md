# Gifsicle for Windows
Gifsicle for Windows is a fork of [the program Gifsicle](https://github.com/kohler/gifsicle) made to build easily on Windows. Gifsicle manipulates GIF image files. Depending on command line options, it can merge several GIFs into a GIF animation; explode an animation into its component frames; change individual frames in an animation; turn interlacing on and off; add transparency; add delays, disposals, and looping to animations; add and remove comments; flip and rotate; optimize animations for space; change images' colormaps; and other things.

The Gifsicle package comes with NO WARRANTY, express or implied, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose.

## Where to download
Nightly binaries are available on the [releases](https://github.com/CoolOppo/Gifsicle-for-Windows/releases) page. You may also download the source code for a release from that page in a `.zip` or `.tar.gz` file. The source code is also available to be downloaded via [the Git repository](https://github.com/CoolOppo/Gifsicle-for-Windows).

## Building
To build Gifsicle for Windows, simply open the solution file in Visual Studio 2013.2 CTP (or newer) and build the solution! You will find the file `Gifsicle.exe` in the `Release` directory.


## Contact
Please email [Eddie Kohler](ekohler@gmail.com) if you have trouble building or running Gifsicle, or if you have suggestions or patches. If you are having trouble with Windows-specific functionality, you can contact me with an issue on GitHub!


## Copyright/License
~~All~~ Most of the source code is Copyright (C) 1997-2013 Eddie Kohler.

Permission is granted to copy, distribute, or alter Gifsicle, whole or in part, as long as source code copyright notices are kept intact, with the following restriction: Developers or distributors who plan to use Gifsicle code, whole or in part, in a product whose source code will not be made available to the end user -- more precisely, in a context which would violate the GPL -- MUST contact the author and obtain permission before doing so.


## Authors
Eddie Kohler <ekohler@gmail.com>
http://www.read.seas.harvard.edu/~kohler/
He wrote it.

Anne Dudfield <anne@mazunetworks.com>
http://www.frii.com/~annied/
She named it.

David Hedbor <david@hedbor.org>
Many bug reports and constructive whining about the optimizer

Emil Mikulic <darkmoon@connexus.net.au>
Helped port to Win32

Hans Dinsen-Hansen <dino@danbbs.dk>
http://www.danbbs.dk/~dino/
Adaptive tree method for GIF writing

CoolOppo
https://github.com/CoolOppo/
Forked Gifsicle and created Gifsicle for Windows