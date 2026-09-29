# Harvard R User Group - `plumber` + `future`: Async Web APIs

Talk given at the [R User Group at Harvard Data Science Initiative](https://www.youtube.com/c/RUserGroupatHarvardDataScienceInitiative/videos)

<table style="margin:0px">
  <tr>
    <td><a href="https://www.rplumber.io/"><img src="images/plumber.png" height="100px" style="padding: 10px;"></a></td>
    <td vlign="center">+</td>
    <td><a href="https://github.com/HenrikBengtsson/future"><img src="images/future.20200115.1200dpi.png" height="100px" style="padding: 10px;"></a></td>
  </tr>
</table>

## Slides

* Recording: https://www.youtube.com/watch?v=eHrzsIGY0so

* HTML: http://schloerke.com/presentation-2021-08-12-harvard-plumber-async


## Resources for learning more

* [`plumber` webpage](https://www.rplumber.io/)
  * An API Generator for R

* [`future` webpage](https://github.com/HenrikBengtsson/future)
  * Unified Parallel and Distributed Processing in R for Everyone

* [`promises` webpage](https://rstudio.github.io/promises/)
  * Abstractions for Promise-Based Asynchronous Programming


## Abstract

`plumber` is an R package that allows users to create web APIs by decorating R functions using `roxygen2`-like comments. In the latest release, asynchronous code (using `future` or `promises`) may be inserted at any stage of a `plumber` route execution, enabling parallel processing using multiple workers. In this talk, I will go through how you can set up your own asynchronous `plumber` API to leverage your full computing potential.
