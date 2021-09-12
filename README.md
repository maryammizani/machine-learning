# References:
https://github.com/amueller/introduction_to_ml_with_python
https://github.com/jakevdp/PythonDataScienceHandbook


# Install
Anaconda Python 3.8 (or previous Anaconda Python)
https://www.anaconda.com/products/individual-d

# Settting up conda environment
To setup Anaconda Python in a terminal or Anaconda prompton Windows:

$ conda create --name env-ml python=3.8 anaconda
$ conda activate env-ml
$ conda install -c conda-forge graphviz python-graphviz
$ conda install -c districtdatalabs yellowbrick=1.3
$ pip install mglearn(optional)
$ pip install nbdime

# Python and Jupyter notebooks
$ jupyter notebook
or
$ jupyter lab


import sys
print("Python version:", sys.version)


import pandas as pd
print("pandas version:", pd.__version__)


import matplotlib
print("matplotlib version:", matplotlib.__version__)


import numpy as np
print("NumPy version:", np.__version__)


import scipy as sp
print("SciPy version:", sp.__version__)


import IPython
print("IPython version:", IPython.__version__)


import sklearn
print("scikit-learn version:", sklearn.__version__)


import yellowbrick
print("yellowbrick version:", yellowbrick.__version__)