# pdf-usletter-to-a4
This python skript converts US letter PDFs to A4 PDFs using ghostscript and pdfcrop.

## Usage
    pdf-usletter-to-a4 [-h] [--margins MARGINS] [-o OUTPUT] [-p]
                       inputfiles [inputfiles ...]

    positional arguments:
      inputfiles         PDF files to convert (at least one)

    optional arguments:
      -h, --help         show this help message and exit
      --margins MARGINS  Margin argument passed to pdfcrop in bp units (see
                         http://tex.stackexchange.com/a/8337/48855 for unit
                         conversion). Defaults to 28.34677≈1cm
      -o OUTPUT, --output OUTPUT
                         Output file name (ignored when multiple input files
                         given)
      -p, --print        Open okular print dialog after conversion

## Requirements
* pdfcrop
* ghostscript
* okular (for `--print` option)

## Installation
The *pdf-usletter-to-a4* script can be used right away without installation.

If you want to add a context menu entry like "Open With..." → "Print as A4", make sure the script is in your PATH and add the *pdf-usletter-to-a4.desktop* file to your `~/.local/share/applications/` folder.

## License

Copyright © 2016 Piotr Orzechowski. This software is released under the MIT License.
