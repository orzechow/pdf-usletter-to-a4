# pdf-usletter-to-a4
This python skript converts US letter PDFs to A4 PDFs using ghostscript and pdfcrop.

## Usage
    pdf-usletter-to-a4 [-h] [--margins MARGINS] inputfiles [inputfiles ...]

    positional arguments:
      inputfiles         PDF files to convert (at least one)

    optional arguments:
      -h, --help         show this help message and exit
      --margins MARGINS  Margin argument passed to pdfcrop in bp units (see
                         http://tex.stackexchange.com/a/8337/48855 for unit
                         conversion). Defaults to 28.34677≈1cm

## Requirements
* pdfcrop
* ghostscript

## License

Copyright © 2016 Piotr Orzechowski. This software is released under the MIT License.
