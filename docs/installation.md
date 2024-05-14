# Installation

### Python: pyEDM
```
pip install pyEDM
```

See: [pyEDM on PyPI](https://pypi.org/project/pyEDM/)

### Jupyter Notebook
A GUI front-end for pyEDM is available at [jpyEDM](https://github.com/SugiharaLab/jpyEDM#empirical-dynamic-modeling-edm-jupyter-notebook)

### R: rEDM
```
install.packages("rEDM")
```

See: [rEDM](https://github.com/SugiharaLab/rEDM "rEDM")

## Note
For OS's not supported by CRAN or PyPI, the packages can be built
from github. Please see:
[pyEDM](https://github.com/SugiharaLab/pyEDM "pyEDM"), or, 
[rEDM](https://github.com/SugiharaLab/rEDM "rEDM").

Version 1.x of pyEDM and rEDM rely on the [LAPACK](http://www.netlib.org/lapack/) libraries. If you build the package, or build the host system (R or python), you will need to ensure a working LAPACK installation. pyEDM version 2.x does not have this dependence. 
