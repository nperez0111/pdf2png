PDFToPNG - A simple batch / bash script to convert pdfs to multiple PNGs
============================================================

Usage
------------

``pdf2png [OPTIONS] FILE``

Options
--------

        -h   ... this help
        -a   ... convert all pages
        -f N ... from page number N
        -t N ... to page number N
        -p N ... only page N (default N = 1)
        -d N ... resolution in dpi (default N = 300)
        -x N ... bitmap  width in pixel (if y not given, save aspect ratio)
        -y N ... bitmap height in pixel (if x not given, save aspect ratio)
        -u N ... unsharp radius (default N = 1.0)
        -c N ... number of colors (default N = 16777216)


What this does is convert each page of the pdf to PNGs

Installation
-------------

1. You could have [ImageMagick](http://www.imagemagick.org/script/index.php) installed but I have already added convert.exe in the project folder.
	* (This converts many image formats into bmp)
2. You could have Ghostscript installed but I have already added gs.exe in the project folder.
3. You should probably add this to your path to use it without having to copy it to every folder you want to use it on.
	* Just run addToPath.bat file to add it to your path.
	* Alternatively if you are using another console emulator, copy this to its bin folder.
4. Just use it.

Dependencies
------------

This assumes that you have the following commands available as well as the ability to run bash files:
	* rm
	* grep
	* awk
	* bash
	* getopts