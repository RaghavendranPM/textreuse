This is a preventative maintenance release of the `textreuse` package. It fixes
tests that will fail when the in-development version of the BH package is 
released.

## Test environments

* local OS X 10.11.6 install: R-release
* Ubuntu 14.04 (on Travis-CI): R-devel, R-release, R-oldrel
* Win-builder: R-devel, R-release

## R CMD check results

There were two NOTEs. 

There was one NOTE about this being a updated version of the package. The NOTE mentions three possible misspelled words, all of which are correctly spelled proper nouns or terms of art.

Win-builder reported one NOTE about large components, but these are just some sample text files for testing and demonstration purposes.
