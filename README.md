latex-assignment-template
=======================
A simple $\LaTeX$ template for assignments! 

**Note**: This fork was built with **xelatex** in mind, compatibility with other
options is not guaranteed. That said, this can probably be achieved by deleting
the font settings section of the template.
## Features
Originally forked from https://github.com/jdavis/latex-homework-template, this
version makes a couple of minor changes allowing for:
- A slightly more modern overall presentation;
- More control over font choice;
- In-line question statements (see screenshots below).

## Screenshots

### The Cover Page:

![Cover page](/images/example-pg1.png)

### Big Oh Example Problem:
![Example problems 1](/images/example-pg2.png)

### Automata & Pseudocode Problems:
![Example problems 2](/images/example-pg3.png)

## Installing

1. First you'll need LaTeX. Instructions on obtaining it can be found here:
   http://latex-project.org/ftp.html
2. Clone or otherwise download [template.tex](/template.tex).
3. Compiling from the command line will look like the following:

   ```bash
   $ latexmk template.tex
   ```
4. Or you can use texshop or a similar native client to typeset the
   LaTeX file.