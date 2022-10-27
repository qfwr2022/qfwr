# **`qfwr`**

The goal of **`qfwr`** is to provide interactive tutorials and some helper 
tools for my course _"Quantitative Finance with R"_ offered in 
Department of Finance, School of Management, Xiamen University, PRC. I hope it will facilitate and enhance our teaching and learning experience.

## Installation

You can install this version of **`qfwr`** from [github](https://github.com/qfwr2022/qfwr) with: 

``` r
# install.packages("devtools")
remotes::install_github("qfwr2022/qfwr")

```

## Example

Currently there are only a handful of exported functions in **`qfwr`**: 
`qfwr_ls()`, `qfwr_ex()`, `qfwr_lab()` and `qfwr_key()`. 

Some basic examples will show:

``` r
## list all interactive exercises in package *qfwr*
qfwr_ls()

## run an interactive exercise
qfwr_ex("L05")

## run a hands-on lab exercise
# qfwr_lab("L06")

## show answer key for lab exercise
# qfwr_key("L06", "ex1")

```

Of course, you can also start `qfwr`'s interactive exercises in RStudio's **Tutorial** panel directly once installed.
