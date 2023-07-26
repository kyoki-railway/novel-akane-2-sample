ハックしないで監査役 EPUB Generation script sample
=========

This is sample script to generate EPUB using Vivliostyle.

How to run:

```sh
# install 
yarn install

# output files for printing (source for PDF generation) to _build/dir
npx gulp print

# output EPUB files to _release/ dir
npx gulp epub

```

The main ideas of this script are as follows:

* Creating manuscripts for print also in EPUB format.
* Preparing print-specific CSS, EPUB-specific CSS (and common CSS referenced from both), and switching between print and EPUB at build time using arguments.

