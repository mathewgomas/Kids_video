## Installation

Install from pip

```bash
pip install pip
```
 https://pypi.org/project/pip/
   : PyPI

 https://pypi.org/project/pip
   : PyPI - Python Version

pip is the `package installer`_ for Python. You can use pip to install packages from the `Python Package Index`_ and other indexes.

Please take a look at our documentation for how to install and use pip:

* `Installation`_
* `Usage`_

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/binder-examples/python-conda_pip/master?filepath=index.ipynb)

If you use `environment.yml`, then Binder will use a Miniconda distribution
to install your packages. However, you may still want to use `pip`. In
this case, you should **not** use a `requirements.txt` file, but instead, use
a `- pip` section in `environment.yml`. 
