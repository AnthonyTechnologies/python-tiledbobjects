Installation
============

PyPI (pip) is the recomended way to install Tiledbobjects, but GitHub can also be used. If you want to run the examples
and Jupyter tutorials included in this repository, you should clone and install from GitHub.


PyPI
----
You can install tiledbobjects using pip:

.. code-block:: bash

   pip install tiledbobjects


GitHub
------

Install the latest code from the main branch without cloning:

.. code-block:: bash

   pip install "git+https://github.com/AnthonyTechnologies/python-tiledbobjects.git@main"


GitHub Clone
------------

Installing a github clone can be useful for either exploring the examples and tutorials and/or contributing
tiledbobjects.

For only exlporing examples and tutorials:

.. code-block:: bash

   git clone https://github.com/AnthonyTechnologies/python-tiledbobjects.git
   cd python-tiledbobjects
   pip install .[jupyter]

For contributing/developing tiledbobjects:

.. code-block:: bash

   git clone https://github.com/AnthonyTechnologies/python-tiledbobjects.git
   cd python-tiledbobjects
   pip install -e .[dev]
