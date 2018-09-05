# Build NEON Slide Decks

Contributors:
Jonah Duckles, Leah Wasser, Megan Jones

A markdown based system to build NEON education modules using reveal.js.  This repo was based on the format used by DataOne. 

## Introduction
This repository takes a markdown file (pandoc flavored syntax) and builds it to
a reveal.js responsive slide show.

To get going

1. make sure reveal.js is setup as a submodule
2. clone the repository
3. make sure pandoc is installed on your local machine
4. at the command line type `make html` -- all files with an .md extension will be built.

To be able to build locally, you need to make sure that the reveal.js files 
also clone.  
`git submodule add https://github.com/hakimel/reveal.js reveal.js` and or 
`git submodule update --init --recursive`
in the command line.

