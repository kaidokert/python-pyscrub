========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - | |github-actions|
        | |coveralls| |codecov|
        | |scrutinizer|
    * - package
      - | |commits-since|

.. |github-actions| image:: https://github.com/kaidokert/python-pyscrub/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/kaidokert/python-pyscrub/actions

.. |coveralls| image:: https://coveralls.io/repos/github/kaidokert/python-pyscrub/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://coveralls.io/github/kaidokert/python-pyscrub?branch=main

.. |codecov| image:: https://codecov.io/gh/kaidokert/python-pyscrub/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://app.codecov.io/github/kaidokert/python-pyscrub

.. |commits-since| image:: https://img.shields.io/github/commits-since/kaidokert/python-pyscrub/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/kaidokert/python-pyscrub/compare/v0.0.0...main


.. |scrutinizer| image:: https://img.shields.io/scrutinizer/quality/g/kaidokert/python-pyscrub/main.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/kaidokert/python-pyscrub/


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install pyscrub

You can also install the in-development version with::

    pip install https://github.com/kaidokert/python-pyscrub/archive/main.zip


Documentation
=============


To use the project:

.. code-block:: python

    import pyscrub
    pyscrub.longest()


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
