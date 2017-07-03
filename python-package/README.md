MLBox, Machine Learning Box
===========================

__MLBox is a powerful Automated Machine Learning python library.__

_It is compatible with:_ __Python 2.7__. (Python 3.3-3.6 very soon...) & __64-bit version only__ (32-bit python is not supported) <br/>
_Operating system:_ __Linux__. (MacOS & Windows very soon...)


## Preparation 

First, make sure you have [setuptools](https://pypi.python.org/pypi/setuptools) installed. <br/>
Since MLBox package contains C++ source code, check that the following requirements are installed, otherwise please proceed below: 

* **[gcc](https://gcc.gnu.org/)** 

.. code-block:: console

    $ sudo apt-get install build-essential
    
* **[cmake](https://cmake.org/)** : 

.. code-block:: console

    $ pip install cmake
   

## Dev version


A 2.3 dev-version for MLBox is also available on the __branch "2.3-dev"__ ! It provides some interesting new features. Please refer to [HISTORY](https://github.com/AxeldeRomblay/MLBox/blob/master/HISTORY.rst). __It depends on sklearn-0.19.dev0 which is not a stable version at the moment.__

If you want, you can have a try: 

* Clone or download sklearn-0.19.dev0 from the github: https://github.com/scikit-learn/scikit-learn
* Install sklearn-0.19.dev0: 

    .. code-block:: console

        $ cd scikit-learn-master/
        $ python setup.py install 

* Clone or download MLBox-2.3.dev0 from the '2.3-dev' branch. 
* Install MLBox-2.3.dev0: 

    .. code-block:: console

        $ cd python-package/
        $ python setup.py install 

    or:

    .. code-block:: console

        $ cd python-package/dist/
        $ pip install *.whl



