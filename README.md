# Project for using GARCH modeling in predicting investment funds volatility

## The final project for finances course in UCU Spring'20
This project dedicated to the research on how generalized autoregressive conditional heteroskedasticity (GARCH) models can be applied for analyzing investment funds volatility.

As a dataset for the project we chose such funds:
* Vanguard Total Stock Market Index Fund;
* Blackrock;
* State Street Corporation;
* JPMorgan Chase & Co;
* The Bank of New York Mellon Corporation;
* Allianz SE.

The main R package in the project for using the GARCH model is [rugarch](https://cran.r-project.org/web/packages/rugarch/index.html).

Data loading and cleaning proceeded with R package [dplyr](https://cran.r-project.org/web/packages/dplyr/index.html).

The R package [xts](https://cran.r-project.org/web/packages/xts/index.html) was used to work with time series.

For applying the "rolling window" approach we used R package [PerformanceAnalytics](https://cran.r-project.org/web/packages/PerformanceAnalytics/index.html).

For visualization, we used the R package [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html).

For the testing hypothesis of the correctness of the predictions, we conducted the Ljung-Box test and tested GARCH model coefficients for robustness.

### This project was created together with [Khrystyna Kubatska](https://github.com/kubatska)
