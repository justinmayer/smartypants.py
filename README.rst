smartypants |build-status| |pypi-version| |downloads| |repology|
================================================================

smartypants_ is a Python fork of SmartyPants__.

.. _smartypants: https://github.com/justinmayer/smartypants.py
__ SmartyPantsPerl_
.. _SmartyPantsPerl: https://daringfireball.net/projects/smartypants/



Installation
------------

To install it:

.. code:: sh

  python -m pip install smartypants


Quick usage
-----------

To use it as a module:

.. code:: python

  import smartypants

  text = '"SmartyPants" is smart, so is <code>smartypants</code> -- a Python port'
  print(smartypants.smartypants(text))

To use the command-line script ``smartypants``:

.. code:: sh

  echo '"SmartyPants" is smart, so is <code>smartypants</code> -- a Python port' | smartypants

Both produce::

  &#8220;SmartyPants&#8221; is smart, so is <code>smartypants</code> &#8212; a Python port


More information
----------------

* Documentation_
* `Source code`_
* PyPI_

.. _documentation: https://smartypants.readthedocs.io
.. _Source code: smartypants_
.. _PyPI: https://pypi.org/project/smartypants/

.. |build-status| image:: https://img.shields.io/github/actions/workflow/status/justinmayer/smartypants.py/ci.yml?branch=main
   :target: https://github.com/justinmayer/smartypants.py/actions/workflows/ci.yml?query=branch%3Amain
   :alt: GitHub Actions CI: continuous integration status
.. |pypi-version| image:: https://img.shields.io/pypi/v/smartypants.svg
   :target: https://pypi.org/project/smartypants/
   :alt: PyPI: the Python Package Index
.. |downloads| image:: https://img.shields.io/pypi/dm/smartypants.svg
   :target: https://pypi.org/project/smartypants/
   :alt: Monthly Downloads from PyPI
.. |repology| image:: https://repology.org/badge/tiny-repos/python%3Asmartypants.svg
   :target: https://repology.org/project/python%3Asmartypants/versions
   :alt: Repology: the packaging hub
