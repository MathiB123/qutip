QuTiP: Quantum Toolbox in Python
================================

[A. Pitchford](https://github.com/ajgpitch),
[C. Granade](https://github.com/cgranade),
[A. Grimsmo](https://github.com/arnelg),
[N. Shammah](https://github.com/nathanshammah),
[S. Ahmed](https://github.com/quantshah),
[N. Lambert](https://github.com/nwlambert),
[E. Giguère](https://github.com/ericgig),
[B. Li](https://github.com/boxili),
[J. Lishman](https://github.com/jakelishman),
[S. Cross](https://github.com/hodgestar),
[A. Galicia](https://github.com/AGaliciaMartinez),
[P. D. Nation](https://github.com/nonhermitian),
and [J. R. Johansson](https://github.com/jrjohansson)

[![Build Status](https://github.com/qutip/qutip/actions/workflows/tests.yml/badge.svg?branch=master)](https://github.com/qutip/qutip/actions/workflows/tests.yml)
[![Coverage Status](https://img.shields.io/coveralls/qutip/qutip.svg?logo=Coveralls)](https://coveralls.io/r/qutip/qutip)
[![Maintainability](https://api.codeclimate.com/v1/badges/df502674f1dfa1f1b67a/maintainability)](https://codeclimate.com/github/qutip/qutip/maintainability)
[![license](https://img.shields.io/badge/license-New%20BSD-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![PyPi Downloads](https://img.shields.io/pypi/dm/qutip?label=downloads%20%7C%20pip&logo=PyPI)](https://pypi.org/project/qutip)
[![Conda-Forge Downloads](https://img.shields.io/conda/dn/conda-forge/qutip?label=downloads%20%7C%20conda&logo=Conda-Forge)](https://anaconda.org/conda-forge/qutip)

> **Note**
>
> The master branch now contains the alpha version of QuTiP 5. This is major
> revision that breaks compatibility in many small ways withh QuTiP 4.7.
>
> If you need to track QuTiP 4.7 changes or submit pull requests for 4.7,
> please use the `qutip-4.7.X` branch.
>
> If you need to track QuTiP 5 changes or submit  pull request for 5,
> please use the `master` branch (and not the `dev.major` branch).
>
> The change to master happened on 16 January 2023 in commit @fccec5d.

QuTiP is open-source software for simulating the dynamics of closed and open quantum systems.
It uses the excellent Numpy, Scipy, and Cython packages as numerical backends, and graphical output is provided by Matplotlib.
QuTiP aims to provide user-friendly and efficient numerical simulations of a wide variety of quantum mechanical problems, including those with Hamiltonians and/or collapse operators with arbitrary time-dependence, commonly found in a wide range of physics applications.
QuTiP is freely available for use and/or modification, and it can be used on all Unix-based platforms and on Windows.
Being free of any licensing fees, QuTiP is ideal for exploring quantum mechanics in research as well as in the classroom.

Support
-------

[![Unitary Fund](https://img.shields.io/badge/Supported%20By-UNITARY%20FUND-brightgreen.svg?style=flat)](https://unitary.fund)
[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

We are proud to be affiliated with [Unitary Fund](https://unitary.fund) and [numFOCUS](https://numfocus.org).

[Nori's lab](https://dml.riken.jp/) at RIKEN and [Blais' lab](https://www.physique.usherbrooke.ca/blais/) at the University of Sherbrooke
have been providing developers to work on QuTiP.

We also thank Google for supporting us by financing GSoC student to work on the QuTiP as well as [other supporting organizations](https://qutip.org/#supporting-organizations) that have been supporting QuTiP over the years.


Installation
------------

[![Pip Package](https://img.shields.io/pypi/v/qutip?logo=PyPI)](https://pypi.org/project/qutip)
[![Conda-Forge Package](https://img.shields.io/conda/vn/conda-forge/qutip?logo=Conda-Forge)](https://anaconda.org/conda-forge/qutip)

QuTiP is available on both `pip` and `conda` (the latter in the `conda-forge` channel).
You can install QuTiP from `pip` by doing

```bash
pip install qutip
```

to get the minimal installation.
You can instead use the target `qutip[full]` to install QuTiP with all its optional dependencies.
For more details, including instructions on how to build from source, see [the detailed installation guide in the documentation](https://qutip.org/docs/latest/installation.html).

All back releases are also available for download in the [releases section of this repository](https://github.com/qutip/qutip/releases), where you can also find per-version changelogs.
For the most complete set of release notes and changelogs for historic versions, see the [changelog](https://qutip.org/docs/latest/changelog.html) section in the documentation.


The pre-release of QuTiP 5.0 is available on PyPI and can be installed using pip:

```bash
pip install --pre qutip
```

This version breaks compatibility with QuTiP 4.7 in many small ways.
Please see the [changelog](https://github.com/qutip/qutip/blob/master/doc/changelog.rst) for a list of changes, new features and deprecations.
This version should be fully working. If you find any bugs, confusing documentation or missing features, please create a GitHub issue.


Documentation
-------------

[![Documentation Status - Latest](https://readthedocs.org/projects/qutip/badge/?version=latest)](https://qutip.readthedocs.io/en/latest/?badge=latest)

The documentation for the latest [stable release](https://qutip.readthedocs.io/en/latest/) and the [master](https://qutip.readthedocs.io/en/master/) branch is available for reading on Read The Docs.

The documentation for official releases, in HTML and PDF formats, can be found in the [documentation section of the QuTiP website](https://qutip.org/documentation.html).

The latest development documentation is available in this repository in the `doc` folder.

A [selection of demonstration notebooks is available](https://qutip.org/tutorials.html), which demonstrate some of the many features of QuTiP.
These are stored in the [qutip/qutip-tutorials repository](https://github.com/qutip/qutip-tutorials) here on GitHub.


Contribute
----------

You are most welcome to contribute to QuTiP development by forking this repository and sending pull requests, or filing bug reports at the [issues page](https://github.com/qutip/qutip/issues).
You can also help out with users' questions, or discuss proposed changes in the [QuTiP discussion group](https://groups.google.com/g/qutip).
All code contributions are acknowledged in the [contributors](https://qutip.org/docs/latest/contributors.html) section in the documentation.

For more information, including technical advice, please see the ["contributing to QuTiP development" section of the documentation](https://qutip.org/docs/latest/development/contributing.html).


Citing QuTiP
------------

If you use QuTiP in your research, please cite the original QuTiP papers that are available [here](https://dml.riken.jp/?s=QuTiP).
