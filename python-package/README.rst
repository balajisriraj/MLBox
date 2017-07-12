MLBox, Machine Learning Box
===========================

**MLBox is a powerful Automated Machine Learning python library.**

* *It is compatible with:* **Python 2.7, 3.4 - 3.6**. & **64-bit version only** (32-bit python is not supported)
* *Operating system:* **Linux**. (MacOS & Windows very soon...)


Preparation 
-----------

First, make sure you have `setuptools <https://pypi.python.org/pypi/setuptools>`__ installed. Since MLBox package contains C++ source code, check that the following requirements are installed: 

* `gcc <https://gcc.gnu.org/>`__ 

.. code-block:: console

    $ sudo apt-get install build-essential
    
* `cmake <https://cmake.org/>`__  

.. code-block:: console

    $ pip install cmake
   

## Dev version


A **4.0 dev-version for MLBox is also available** on the branch `"4.0-dev" <https://github.com/AxeldeRomblay/MLBox/tree/4.0-dev>`__ ! It provides some interesting new features. Please refer to `HISTORY <https://github.com/AxeldeRomblay/MLBox/blob/master/HISTORY.rst>`__. 

**It depends on sklearn-0.19.dev0 which is not a stable version at the moment.**

If you want, you can have a try: 

* Clone or download sklearn-0.19.dev0 from the github: https://github.com/scikit-learn/scikit-learn
* Install sklearn-0.19.dev0: 

    .. code-block:: console

        $ cd scikit-learn-master/
        $ python setup.py install 

* Clone or download MLBox-4.0.dev from the '4.0-dev' branch. 
* Install MLBox-4.0.dev: 

    .. code-block:: console

        $ cd python-package/
        $ python setup.py install 

    or:

    .. code-block:: console

        $ cd python-package/dist/
        $ pip install *.whl



