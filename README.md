# citest

[![Travis-CI Build Status](https://travis-ci.org/zkamvar/citest.svg?branch=master)](https://travis-ci.org/zkamvar/citest)

The goal of citest is to test the function `utils::citation()`

**Update:** this was fixed by Martin Maechler:    
:tada: https://stat.ethz.ch/pipermail/r-devel/2017-April/074027.html :tada:    
:sparkles: https://github.com/wch/r-source/commit/15d3c233b7ee3c4f269184a9775cfc6d16b5ed2e :sparkles:

## Example

I was having trouble with poppr on travis ci, and Jim Hester
[pointed me to a commit in R-devel][hester] that might be causing the 
hubub. This package investigates that by testing the citation
function in the vignette.

I had initially tested this using [poppr's citation file](https://github.com/grunwaldlab/poppr/blob/master/inst/CITATION)
and then used [boot's citation file](https://github.com/cran/boot/blob/master/inst/CITATION).

[hester]: https://github.com/travis-ci/travis-ci/issues/7549#issuecomment-290776302
