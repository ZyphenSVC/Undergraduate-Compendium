# Undergraduate-Compendium
> A compilation of all of my undergraduate notes, given that I took them.

These curated collection of undergraduate notes, problem sets, and course writeups are from mainly mathematics department from the University of Georgia and also personal studies. The selections in which topics I choose to include are subject to change as we progress and if I have a personal stake or enough to release a writeup.

Given that these notes are over the course of four years, my latex typesetting and explanations of mathematics are also subject to change. It shows improvement overtime and I did not change or modify my original notes heavily except to match this typesetting theme and minor mistakes made.
 
Given that these notes reflect the material I chose to write up during my undergraduate studies, they are also intended to serve as an archive of sorts and a public resource for anyone interested in related coursework. However, relying on my notes to study rather than just reference is something I would not  recommend. Likely there are many mistakes and odd explanations which even I sometimes may not comprehend now, but albeit it will subsist.

## LaTeX Theme
Original preamble was provided by [Altanis](https://github.com/Altanis), all credit goes to them. 

I modified the preamble slightly for my use cases and specifics.

## Contents

This repository will include material from topics such as:

- Calculus (<b><i>#TODO</i></b>)
- Linear Algebra (<b><i>#TODO</i></b>)
- Elementary Differential Equations (<b><i>#TODO</i></b>)
- Introduction to Proofs (<b><i>#TODO</i></b>)
- [Real Analysis](https://github.com/ZyphenSVC/Undergraduate-Compendium/blob/master/out/RealAnalysis.pdf)
- [Abstract Algebra](https://github.com/ZyphenSVC/Undergraduate-Compendium/blob/master/out/AbstractAlgebra.pdf)
- [Algebraic Geometry](https://github.com/ZyphenSVC/Undergraduate-Compendium/blob/master/out/AlgebraicGeometry.pdf)
- Combinatorics (<b><i>#TODO</i></b>)
- Point Set Topology (<b><i>#TODO</i></b>)
- Algebraic Topology (<b><i>#TODO</i></b>)
- Elliptic Curves (<b><i>#TODO</i></b>)
- Hartshorne (<b><i>#TODO</i></b>)
- Complex Geometry (<b><i>#TODO</i></b>)
- Undergraduate Research (<b><i>#TODO</i></b>)
- Hodge Theory (<b><i>#TODO</i></b>)
- Graduate Algebra (<b><i>#TODO</i></b>)
- Commutative Algebra (<b><i>#TODO</i></b>)

## Structure

The `out` folder will contain specific course notes. These notes are not intended to be polished textbooks. Some sections may be incomplete, abbreviated, or more proof-oriented than lecture-oriented. Errors may still exist, especially in older files

## License

Unless otherwise noted, the written notes and documentation in this repository are licensed under **CC BY 4.0**.

## Acknowledgments

Special thanks to the instructors, mentors, and peers whose courses, discussions, and guidance shaped these notes.

## Compilation

Most files can be compiled with a standard LaTeX engine such as:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex

```

I use

```bash
pdflatex -interaction=nonstopmode -output-directory=./out main.tex
biber --input-directory=./out --output-directory=./out main
pdflatex -interaction=nonstopmode -output-directory=./out main.tex
pdflatex -interaction=nonstopmode -output-directory=./out main.tex
```