


# filelock

> Portable File Locking

[![Linux Build Status](https://travis-ci.org/gaborcsardi/filelock.svg?branch=master)](https://travis-ci.org/gaborcsardi/filelock)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/github/gaborcsardi/filelock?svg=true)](https://ci.appveyor.com/project/gaborcsardi/filelock)
[![](http://www.r-pkg.org/badges/version/filelock)](http://www.r-pkg.org/pkg/filelock)
[![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/filelock)](http://www.r-pkg.org/pkg/filelock)


Place an exclusive or shared lock on a file. It uses `LockFile` on Windows
and `fcntl` locks on Unix-like systems.

## Installation


```r
devtools::install_github("gaborcsardi/filelock")
```

## Usage


```r
library(filelock)
```

## License

MIT © RStudio
