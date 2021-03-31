# Installation

### Python: pyEDM
```
pip install pyEDM
```

See: [pyEDM on PyPI](https://pypi.org/project/pyEDM/)

### R: rEDM
```
install.packages("rEDM")
```
For the latest development code:
```
install.packages("devtools")
```
```
devtools::install_github("SugiharaLab/rEDM")
```

See: [rEDM](https://github.com/SugiharaLab/rEDM "rEDM")

## Note
For OS's not supported by CRAN or PyPI, the packages can be built
from github. Please see:
[pyEDM](https://github.com/SugiharaLab/pyEDM "pyEDM"), or, 
[rEDM](https://github.com/SugiharaLab/rEDM "rEDM").

EDM relies on the LAPACK libraries. If you build the package, or build the host system (R or python), you will need to ensure a working LAPACK installation.
