Parsing & Syntactic Processing
==============================

Overview
--------

This is the primary course website for Parsing & Processing (Lin 630), offered by the [Department of Linguistics][department] at [Stony Brook University][sbu].
For a brief list of topics, check the [syllabus][syllabus].

This repository is publicly accessible and hosts the LaTeX source code for the lecture notes.
Compiled pdfs of each chapter are available in the [pdf][pdf] folder.


Compilation Instructions
------------------------

If you want to compile the lecture notes yourself, or use them as the basis for your own course, carefully follow the steps below.

1. Make sure you have all necessary software installed and set up correctly, in particular

  - a recent LaTeX distribution with `Tikz >= 3.00` and recent versions of `minted` and `forest`
  - the Python `pygments` package (required by `minted`)

2. Clone the repository via git, or download and extract the [zip file](../../archive/master.zip).
   Note that the project folder will also contain an empty `build` folder, which is used for temporary files to speed up compilation.

3. Use the standard `tex --> pdf` compilation tool chain (**not** `tex --> dvi --> ps --> pdf`!), but make sure that `pdflatex` is run with the parameter `--shell-escape`. 

[department]: http://linguistics.stonybrook.edu
[pdf]: ../../tree/master/pdf
[readings]: ../../../readings
[sbu]: http://www.stonybrook.edu
[syllabus]: ../../blob/master/pdf/0_syllabus.pdf?raw=true
