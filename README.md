# latex-worksheet-template

A simple latex template for Computer Science worksheets.

The template file automatically tallies the question count and the
number of pages.  The document displays relevant worksheet information
at the top and bottom of each page (eg, course number, date, page
number, and number of questions).

A
[custom listing file](https://github.com/markroyer/latex-listings-eclipse)
was used for syntax markup.

## Setup

Make sure that you have the Debian `texlive` package installed.

## Usage

You can build the PDF document by typing

```
make
```

in the root of the repository. The file `worksheet.pdf` is the
generated output.

Typing

```
make clean
```

will remove all generated files.

## License

The project is licensed under the terms of the
[GPL3](https://www.gnu.org/licenses/gpl-3.0.en.html) license.

<!--  LocalWords:  texlive pdf
 -->
