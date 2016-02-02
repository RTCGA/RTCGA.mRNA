[![Build Status](http://bioconductor.org/shields/build/devel/data-experiment/RTCGA.mRNA.svg)](http://bioconductor.org/checkResults/devel/data-experiment-LATEST/RTCGA.mRNA/)
# [RTCGA.mRNA](http://bioconductor.org/packages/RTCGA.mRNA/)

A part of [RTCGA](https://github.com/RTCGA) family.

To install development version from GitHub use

````{R}
library(RTCGA)
installTCGA(RTCGA.mRNA")
````

Make sure you have [Rtools](https://cran.r-project.org/bin/windows/Rtools/) installed on your computer, if you are trying `devtools` on Windows.

To install Bioconductor development version use (the same as GitHub development version)

````{R}
BiocInstaller::useDevel() # swiches to devel branchof Bioconductor
source("https://bioconductor.org/biocLite.R") # downloads bioClite function
biocLite("RTCGA.mRNA") # installs a package
````

