.. -*- mode: rst -*-

DIRAC - Pilots
=============
.. image:: https://travis-ci.org/DIRACGrid/Pilot.svg?branch=master
    :target: https://travis-ci.org/DIRACGrid/Pilot
.. image:: https://img.shields.io/coveralls/DIRACGrid/Pilot/master.svg?maxAge=2592000
    :target: https://coveralls.io/github/DIRACGrid/Pilot
.. image:: https://landscape.io/github/DIRACGrid/Pilot/master/landscape.svg?style=flat
   :target: https://landscape.io/github/DIRACGrid/Pilot/master
   :alt: Code Health
DIRAC (Distributed Infrastructure with Remote Agent Control) INTERWARE is a software framework for distributed computing providing a complete solution to one or more user community requiring access to distributed resources. DIRAC builds a layer between the users and the resources offering a common interface to a number of heterogeneous providers, integrating them in a seamless manner, providing interoperability, at the same time as an optimized, transparent and reliable usage of the resources.

DIRAC has been started by the `LHCb collaboration <https://lhcb.web.cern.ch/lhcb/>`_ who still maintains it. It is now used by several communities (AKA VO=Virtual Organizations) for their distributed computing workflows.

Pilots consist of the independent part of the DIRAC system dedicated to the development of Pilot Agents.


Important links
===============

- Official source code repo: https://github.com/DIRACGrid/Pilot
- Support Mailing list: https://groups.google.com/forum/#!forum/diracgrid-forum
- Developers Mailing list: https://groups.google.com/forum/#!forum/diracgrid-develop

Development
===========


Code quality
~~~~~~~~~~~~

The contributions are subject to reviews.

Pylint is run regularly on the source code. The .pylintrc file defines the expected coding rules and peculiarities (e.g.: tabs consists of 2 spaces instead of 4)

Testing
~~~~~~~

Unit tests are provided within the source code. Integration, regression and system tests are instead in the tests directory. Run py.test to run all unit tests.
