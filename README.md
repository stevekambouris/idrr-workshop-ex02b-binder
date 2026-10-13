### SORTEE 2026 Workshop 3
### An introduction to using Docker with R for reproducible research
# Example: Calculating a bootstrapped confidence interval (R 3.6.0)

_This repository is set up to be launched as a container on mybinder.org, rather than to be used to build an image with Docker Desktop. For the version of this example that can be used to build an image locally, go to <https://github.com/stevekambouris/idrr-workshop-ex02b-desktop>._

Click the button below to start an instance of the container defined by this repository on mybinder.org.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stevekambouris/idrr-workshop-ex02b-binder/main?urlpath=rstudio)

This Docker image is based on [rocker/binder:3.6.0](https://hub.docker.com/layers/rocker/binder/3.6.0/), which has R version `3.6.0` installed, along with `tidyverse` packages.

**Instructions**
1. Once the container has launched as a result of clicking the above button, you should see an instance of RStudio in your web browser window.
2. There will be two files available, `data_penguins.csv` and `bootstrap_ci.R`.
3. Open `bootstrap_ci.R` in RStudio and run the code from the top, observing the output to the console as you progress.
