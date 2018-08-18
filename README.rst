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
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/open-agroecology-tools/badge/?style=flat
    :target: https://readthedocs.org/projects/open-agroecology-tools
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/bcbernardo/open-agroecology-tools.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/bcbernardo/open-agroecology-tools

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/bcbernardo/open-agroecology-tools?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/bcbernardo/open-agroecology-tools

.. |requires| image:: https://requires.io/github/bcbernardo/open-agroecology-tools/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/bcbernardo/open-agroecology-tools/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/bcbernardo/open-agroecology-tools/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/bcbernardo/open-agroecology-tools

.. |version| image:: https://img.shields.io/pypi/v/open-agroecology-tools.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/open-agroecology-tools

.. |commits-since| image:: https://img.shields.io/github/commits-since/bcbernardo/open-agroecology-tools/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/bcbernardo/open-agroecology-tools/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/open-agroecology-tools.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/open-agroecology-tools

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/open-agroecology-tools.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/open-agroecology-tools

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/open-agroecology-tools.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/open-agroecology-tools


.. end-badges

Tools for designing and managing diversified agroecosystems.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install open-agroecology-tools

Documentation
=============

https://open-agroecology-tools.readthedocs.io/

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
