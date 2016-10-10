========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/cromulatron-bot/badge/?style=flat
    :target: https://readthedocs.org/projects/cromulatron-bot
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/jkahn/cromulatron-bot.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/jkahn/cromulatron-bot

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/jkahn/cromulatron-bot?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/jkahn/cromulatron-bot

.. |requires| image:: https://requires.io/github/jkahn/cromulatron-bot/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/jkahn/cromulatron-bot/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/jkahn/cromulatron-bot/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/jkahn/cromulatron-bot

.. |version| image:: https://img.shields.io/pypi/v/cromulatron.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/cromulatron

.. |downloads| image:: https://img.shields.io/pypi/dm/cromulatron.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/cromulatron

.. |wheel| image:: https://img.shields.io/pypi/wheel/cromulatron.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/cromulatron

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/cromulatron.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/cromulatron

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/cromulatron.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/cromulatron


.. end-badges

A Twitter bot that posts sentences for grammaticality judgments.

* Free software: BSD license

Installation
============

::

    pip install cromulatron

Documentation
=============

https://cromulatron-bot.readthedocs.io/

Development
===========

To run the all tests run::

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
