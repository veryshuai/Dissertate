# Dissertate: a LaTeX dissertation template [![Build Status](https://travis-ci.org/suchow/Dissertate.svg?branch=master)](https://travis-ci.org/suchow/Dissertate)


This package provides all the files needed to support the production and typesetting of a PhD dissertation at Harvard, Princeton, NYU, and Penn State though it can easily be adapted to meet the requirements of other schools. The format and styling is based closely on the requirements published by each university's registrar.

This version is less of a template, and the actual production copy of the dissertation of David Jinkins at Penn State.  Most of the changes from the original version were to meet Penn State's dissertation format requirements, but a few were also specific to my dissertation, such as reducing the whitespace on the acknowledgments section in order to fit more thank yous on one page.


## Getting started
1. Install LaTeX. For Mac OS X, we recommend MacTex (http://tug.org/mactex/); for Windows, MiKTeX (http://miktex.org/); and for Ubuntu, Tex Live (`sudo apt-get install texlive-full`)
2. Install the default fonts: EB Garamond, Lato, and Source Code Pro. The files are provided in `fonts/EB Garamond`, `fonts/Lato`, and `fonts/Source Code Pro`.
3. Pick your school by editing line 6 of `dissertation.tex` to use the option `Harvard`, `Princeton`, or `NYU`, depending on your school.
4. Personalize the document by filling out your name and all the other info in `frontmatter/personalize.md`.
5. Build your dissertation with `build.command`, located in the `scripts` directory (e.g., you can `cd` into the main directory and then run `./scripts/build.command`).

## FAQ

### How do I make the text justified instead of ragged right?
Remove or comment out the line `\RaggedRight` from the .cls file.

## Acknowledgments
Thanks to Andrew Leifer for many code and README contributions and to Clemens Eppner for the Ubuntu instructions.
