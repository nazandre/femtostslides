FemtoSTSlides
==================

FemtoSTSlides: an unofficial Femto-ST theme for LaTex-Beamer!

This theme is based on ensislides, the unofficial Ensimag theme from Matthieu Moy available at http://www-verimag.imag.fr/~moy/ensitools/beamer/ .

It comes with many freeware icons from Icojam: http://www.icojam.com/.

# Dependencies
If using our Makefile :
- latexmk : used to compile the Tex files into pdf.
- gs - Ghostscript : used to compress pdf.

Otherwise, you can simply use the LaTex compiler of your choice such as pdflatex!

# Usage
In a terminal, enter "Make". This generates two pdf files: example.pdf and example-compressed.pdf, a compressed version of example.pdf.

# Content
- femtostslides.sty: latex style file.
- fig/: some useful images (logo, icons, ... ). Icons are from Icojam (http://www.icojam.com/) and are freeware.
- example.tex, example.pdf: an example of presentation using FemtoSTSlide.
- Makefile: Makefile used to compile the provided example of presentation.
- README.md: this readme.

# Future improvements

Include examples with integrated videos and mimic a presenter mode.
