# LaTeX_Resume :pushpin:
A Resume made with LaTeX, feel free to edit and use as you please.

## Compiling to PDF
I found that the following sequence of steps works for getting the PDF:
  1. Open up your terminal and `cd` into the directory that contains the *.tex* file
  2. Type the following into your terminal:
  - `$ latex resume.tex`
  - `$ dvips -Ppdf -t letter resume.dvi`
  - `$ ps2pdf resume.ps`

