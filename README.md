
# targets <img src='man/figures/logo.png' align="right" height="139"/>

[![ropensci](https://badges.ropensci.org/401_status.svg)](https://github.com/ropensci/software-review/issues/401)
[![zenodo](https://zenodo.org/badge/200093430.svg)](https://zenodo.org/badge/latestdoi/200093430)
[![R
Targetopia](https://img.shields.io/badge/R_Targetopia-member-blue?style=flat&labelColor=gray)](https://wlandau.github.io/targetopia/)
[![cran](http://www.r-pkg.org/badges/version/targets)](https://cran.r-project.org/package=targets)
[![status](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![check](https://github.com/wlandau/targets/workflows/check/badge.svg)](https://github.com/wlandau/targets/actions?query=workflow%3Acheck)
[![codecov](https://codecov.io/gh/wlandau/targets/branch/main/graph/badge.svg?token=3T5DlLwUVl)](https://codecov.io/gh/wlandau/targets)
[![lint](https://github.com/wlandau/targets/workflows/lint/badge.svg)](https://github.com/wlandau/targets/actions?query=workflow%3Alint)

The `targets` package is a
[Make](https://www.gnu.org/software/make/)-like pipeline toolkit for
Statistics and data science in R. With `targets`, you can maintain a
reproducible workflow without repeating yourself. `targets` skips costly
runtime for tasks that are already up to date, runs the necessary
computation with implicit parallel computing, and abstracts files as R
objects. A fully up-to-date `targets` pipeline is tangible evidence that
the output aligns with the code and data, which substantiates trust in
the results.

## Prerequisites

1.  Familiarity with the [R programming
    language](https://www.r-project.org/), covered in [R for Data
    Science](https://r4ds.had.co.nz/).
2.  [Data science workflow management
    techniques](https://rstats.wtf/index.html).
3.  [How to write functions](https://r4ds.had.co.nz/functions.html) to
    prepare data, analyze data, and summarize results in data analysis
    projects.

## How to get started

1.  Watch minutes 6 through 40 of the [New York Open Statistical
    Programming Meetup from
    December 2020](https://youtu.be/Gqn7Xn4d5NI).
2.  Read the [short walkthrough
    chapter](https://wlandau.github.io/targets-manual/walkthrough.html)
    of the [user manual](https://wlandau.github.io/targets-manual/).
3.  Sign up for a free [RStudio Cloud](https://rstudio.cloud) account
    and [click here](https://rstudio.cloud/project/1430691) to open the
    [walkthrough](https://wlandau.github.io/targets-manual/walkthrough.html)
    code. Experiment with functions
    [`tar_make()`](https://wlandau.github.io/targets/reference/tar_make.html)
    and
    [`tar_read()`](https://wlandau.github.io/targets/reference/tar_read.html).
4.  Log into the [cloud
    workspace](https://rstudio.cloud/project/1699460) of the [official
    `targets` short
    course](https://github.com/wlandau/targets-tutorial/blob/main/README.md).
    Work through the exercises in R notebooks
    [`1-functions.Rmd`](https://github.com/wlandau/targets-tutorial/blob/main/1-functions.Rmd),
    [`2-pipelines.Rmd`](https://github.com/wlandau/targets-tutorial/blob/main/2-pipelines.Rmd),
    and
    [`3-changes.Rmd`](https://github.com/wlandau/targets-tutorial/blob/main/3-changes.Rmd).
5.  Try out one of the other [example
    projects](https://wlandau.github.io/targets/index.html#example-projects)
    linked from the [reference
    website](https://wlandau.github.io/targets/index.html#example-projects).

## Installation

You can install the GitHub development version of `targets` to access
the latest features and patches.

``` r
library(remotes)
install_github("wlandau/targets")
```

## Recorded talks

  - [R/Pharma 2020
    (9:24)](https://www.youtube.com/watch?v=GRqKJBaC5g4&list=PLMtxz1fUYA5C0YflXsR8EEAQXfjntlV1H&index=6)
  - [New York Open Statistical Programming Meetup, December 2020
    (1:54:28)](https://youtu.be/Gqn7Xn4d5NI)
  - [LA R Users Meetup, October 2020
    (1:14:40)](https://www.youtube.com/watch?v=Qq25BUxpJu4)

## Documentation

  - [User manual](https://wlandau.github.io/targets-manual): in-depth
    discussion about how to use `targets`.
  - [Reference website](https://wlandau.github.io/targets/): formal
    documentation of all user-side functions, the statement of need, and
    multiple design documents of the internal architecture.
  - [Developer documentation](https://wlandau.github.io/targets-design):
    software design documents for developers contributing to the deep
    internal architecture of `targets`.

## Courses

  - [Official half-day interactive
    tutorial](https://github.com/wlandau/targets-tutorial).

## Example projects

  - [Minimal example](https://github.com/wlandau/targets-minimal).
  - [Machine learning with
    Keras](https://github.com/wlandau/targets-keras).
  - [Validating a Stan model](https://github.com/wlandau/targets-stan).

## Apps

  - [`tar_watch()`](https://wlandau.github.io/targets/reference/tar_watch.html):
    a built-in Shiny app to visualize progress while a pipeline is
    running.
  - [`targetsketch`](https://wlandau.shinyapps.io/targetsketch): a Shiny
    app to help sketch pipelines
    ([app](https://wlandau.shinyapps.io/targetsketch),
    [source](https://github.com/wlandau/targetsketch)).

## The R Targetopia

The R Targetopia consists of specialized workflow frameworks tailored to
individual fields of Statistics and data science, and they use domain
knowledge to abstract away most of the careful planning and engineering
typically required to write pipelines. They leverage the full power of
[`targets`](https://github.com/wlandau/targets) while requiring minimal
expertise with [`targets`](https://github.com/wlandau/targets) itself.
Examples include [`stantargets`](https://github.com/wlandau/stantargets)
and [`tarchetypes`](https://wlandau.github.io/tarchetypes).

## Help

  - Post to the [GitHub issue
    tracker](https://github.com/wlandau/targets/issues) to elicit help
    from the maintainer.
  - The [RStudio Community](https://community.rstudio.com/) forum is
    full of friendly enthusiasts of R and the tidyverse. Use the
    [`targets` tag](https://community.rstudio.com/tag/targets).
  - [Stack Overflow](https://stackoverflow.com/) broadcasts to the
    entire open source community. Use the [`targets-r-package`
    tag](https://stackoverflow.com/questions/tagged/targets-r-package).

## Participation

Development is a community effort, and we welcome discussion and
contribution. By participating in this project, you agree to abide by
the [code of
conduct](https://github.com/wlandau/targets/blob/main/CODE_OF_CONDUCT.md)
and the [contributing
guide](https://github.com/wlandau/targets/blob/main/CONTRIBUTING.md).

## Citation

``` r
citation("targets")
#> Warning in citation("targets"): no date field in DESCRIPTION file of package
#> 'targets'
#> Warning in citation("targets"): could not determine year for 'targets' from
#> package DESCRIPTION file
#> 
#> To cite package 'targets' in publications use:
#> 
#>   William Michael Landau (NA). targets: Dynamic Function-Oriented
#>   'Make'-Like Declarative Workflows.
#>   https://wlandau.github.io/targets/,
#>   https://github.com/wlandau/targets.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {targets: Dynamic Function-Oriented 'Make'-Like Declarative Workflows},
#>     author = {William Michael Landau},
#>     note = {https://wlandau.github.io/targets/, https://github.com/wlandau/targets},
#>   }
```
