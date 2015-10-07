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
In a terminal, enter "Make". This generates two pdf files: example.pdf and example-compressed.pdf, a compressed version of example.pdf. Not all the pdf viewers are able to display videos.

# Content
- femtostslides.sty: latex style file.
- fig/: some useful images (logo, icons, ... ). Icons are from Icojam (http://www.icojam.com/) and are freeware.
- video/femtost.mp4: a video giving an overview of Femto-ST Institut (downloaded from https://www.youtube.com/watch?v=2HCW9sSjtaw).
- example.tex, example.pdf, example-compressed.pdf: an example of presentation using FemtoSTSlides.
- Makefile: Makefile used to compile the provided example of presentation.
- README.md: this readme.

# Future improvements
Mimic a presenter mode.