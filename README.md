# The braids Library

This is the official home of the development repository for the
`braids` library.
This library enables drawing of braid diagrams with PGF/TikZ using a simple syntax.
The braid itself is specified by giving a word in the braid group, and there are many options for styling the strands and for drawing “floors”.

This library was previously published as a separate latex package, which can be found [on CTAN](https://ctan.org/pkg/braids?lang=en).
Since version 2.0, it has been reimplemented as a TikZ library.
If starting with a fresh document, please consider using the new library instead.

## Usage

- Download the files `braids_code.dtx` and `braids.tex`.
- To generate the library files, run `tex braids_code.dtx`.
- To generate the documentation, run `pdflatex braids.tex`.

The generated file `tikzlibrarybraids.code.tex` must be in the same directory with the tex file that uses this library.
(Alternatively, specify some other way that tex uses this version of the library instead of the one included with your tex installation.)

## Tests

To compile the tests, clone this repository and run the commands
`pdflatex tests/braid_pic.tex`
from the root directory of this repository.




