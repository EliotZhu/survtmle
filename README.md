# R/`survtmle`

[![Travis-CI Build
Status](https://travis-ci.org/nhejazi/survtmle.svg?branch=master)](https://travis-ci.org/nhejazi/survtmle)
[![Coverage
Status](https://coveralls.io/repos/github/nhejazi/survtmle/badge.svg?branch=master)
](https://coveralls.io/github/nhejazi/survtmle?branch=master)
[![MIT
license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

> Targeted Minimum Loss-Based Estimation (TMLE) for Survival Analysis and
> Vaccine Sieve Analysis

---

## Description

`survtmle` is an R package designed to use Targeted Minimum Loss-Based
Estimation (TMLE) to compute marginal cumulative incidence estimates in
right-censored survival settings with and without competing risks, including
vaccine sieve analysis. This tool also provides facilities for computing and
obtaining inference for the use of data adaptive target parameters in such
settings.

---

## Installation

- Install the most recent _stable release_:
  `devtools::install_github("benkeser/survtmle")`

- To contribute, install the _development version_:
  `devtools::install_github("benkeser/survtmle", ref = "develop")`

---

## License

&copy; 2016-2017 [David C. Benkeser](http://www.benkeserstatistics.com)

The contents of this repository are distributed under the MIT license. See
below for details:
```
The MIT License (MIT)

Copyright (c) 2016-2017 David C. Benkeser

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
