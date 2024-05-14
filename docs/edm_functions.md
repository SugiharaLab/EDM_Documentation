# API Reference

Version 1.x of [pyEDM](https://github.com/SugiharaLab/pyEDM "pyEDM") and
[rEDM](https://github.com/SugiharaLab/rEDM "rEDM") are wrappers for the [cppEDM library](https://github.com/SugiharaLab/cppEDM "cppEDM"). Version 2.x of [pyEDM](https://github.com/SugiharaLab/pyEDM "pyEDM") uses numpy/scipy instead of cppEDM. 

**Note:** The [Rcpp](https://CRAN.R-project.org/package=Rcpp) wrapper limits rEDM:cppEDM API functions to 20 parameters. As a result the rEDM API does not have full functional access to the EDM API. Users requiring the full API are referred to [pyEDM](https://pypi.org/project/pyEDM/).

**Note:** `SMap` linear system solver regularization: The R [glmnet](https://CRAN.R-project.org/package=glmnet) package does not seperate the model from the data. This prevents integration in rEDM. Users requiring `SMap` regularization are referred to [pyEDM](https://pypi.org/project/pyEDM/).
