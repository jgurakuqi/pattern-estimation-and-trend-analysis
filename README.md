# pattern-estimation-and-trend-analysis

## Table of Contents

- [Description](#Description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

The goal of these examples is to analyse the given datasets to determine whether some models can be established for purposes of prediction, to assess how stepwise prediction behaves with respect to a personally chosen model and determine an unknown trend in the cereal dataset:
- The first two examples harness simple tools for numerical and class predictions, by determining which relationship influences Canadian house prices for the first one and which influences the possibility of the bank's subscribing to the term deposit in the second one.
- The third one compares the results achieved through a stepwise regression with biderectional elimination against those of a personally chosen effective logistic regression on the bank data. In both cases, the aim is to determine the relationship that best predicts whether or not a user has subscribed to the term deposit.
- The fourth one looks for possible trend/patterns in the given cereal data. In particular, the variable that seems to be most interesting to predict is the amount of calories based on the other attributes.


## Installation

The examples require [R](https://cran.rstudio.com/) and [RStudio](https://posit.co/download/rstudio-desktop/) to run, and a series of packages that will be suggested by RStudio when the rmd files are first opened.

## Usage

The outputs are produced as html files, which are already included in the repo. If you need to run the markdowns select the Knit to HTML option (or the more suitable for you).
To view the html files produced in this repository, you can download them (or produce them) and open them in a web browser, or use the following links directly to view those included in the repository
- [Example 1](https://htmlpreview.github.io/?https://github.com/jgurakuqi/trend-analysis/blob/main/ex1_houses_price_forecast.html)
- [Example 2](https://htmlpreview.github.io/?https://github.com/jgurakuqi/trend-analysis/blob/main/ex2_bank_subscription_forecast.html)
- [Example 3](https://htmlpreview.github.io/?https://github.com/jgurakuqi/trend-analysis/blob/main/ex3_stepwise_regression.html)
- [Example 4](https://htmlpreview.github.io/?https://github.com/jgurakuqi/trend-analysis/blob/main/ex4_find_trend.html)


## Contribution

Any contribution with further examples or improvements are welcome.

## License

MIT License

Copyright (c) 2023 Jurgen Gurakuqi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
