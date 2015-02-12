# QuanSDM
## quantitative species distribution modelling


This R package contains functions that allows to "species-distribution-model" continious quantities for few SDM methods, such as 
[random forest](http://cran.r-project.org/web/packages/randomForest/index.html),
[gbm](http://cran.r-project.org/web/packages/dismo/index.html), and
[gam](http://cran.r-project.org/web/packages/mgcv/index.html). It provides means for crossvalidation, various model performance metrics and helper functions for null models, spatial autocorrelation, ... .

----

### Installation
just issue
```
devtools::install_github("janhoo/quansdm")
```
you may need to (`install.packages("devtools")`) first.

Done.






### License

This package is licensed to you under the terms of the [GNU AFFERO GENERAL PUBLIC LICENSE](http://choosealicense.com/licenses/agpl-3.0/) version 3.0 or higher.
