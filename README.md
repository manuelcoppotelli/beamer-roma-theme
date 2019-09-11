ROMA, A SPIFFY THEME FOR BEAMER LATEX
=======================================

## Author
Manuel Coppotelli <manuelcop@gmail.com>

### Contributor 
Andrea Bacciu [andreabac3](http://www.github.com/andreabac3)

## Abstract
Beamer ([https://bitbucket.org/rivanvx/beamer/wiki/Home](https://bitbucket.org/rivanvx/beamer/wiki/Home)) is a LaTeX class that allows you to create
presentations. Beamer contains several full-featured (but a bit ugly) themes, so I wrote this spiffy theme (but with some missing features) called Roma.

The color scheme is taken from the official Sapienza [brand guidelines](http://www.uniroma1.it/sites/default/files/ElementiBase_Brand%20acrhitecture.pdf).

## Overleaf 
### Fastest way
Click on this overleaf link (https://www.overleaf.com/read/rkjvzctxsyvt) and then copy the project in your profile.

### Alternative way
Checkout the [overleaf](https://github.com/manuelcoppotelli/beamer-roma-theme/tree/overleaf) branch and then you can use this project on [Overleaf](https://www.overleaf.com)

## Demo
You can preview an example of presentation made using this theme [here](https://github.com/manuelcoppotelli/beamer-roma-theme/blob/master/examples/roma-demo.pdf).

## Installation
First of all, you have to install Beamer, directly from source or using an
available package for your distro; then install the theme.

### Unix installation
On a Unix system just type in a terminal:

```bash
$ sudo cp -r themes /usr/share/texmf/tex/latex/beamer/
$ sudo texhash
```

### MacOS installation
On MacOS just type in a terminal:

```bash
$ sudo cp -r themes /usr/local/texlive/2015basic/texmf-dist/tex/latex/beamer/
$ sudo texhash
```

## Usage
Now you are ready to use the theme, for documentation read the example files:
roma-demo.tex.
Compiling them you get some slides with documentation:

```bash
$ pdflatex roma-demo.tex
```

## How to use it for slides in Italian or English
Choose the right (main) file, for italian slides select `roma-demo-it.tex`.
Otherwhise, for english slides, use `roma-demo-en.tex`.


## Copyright
Sapienza and DIAG (Department of Computer, Control and Management Engineering)
logos belong to their respective owners.
