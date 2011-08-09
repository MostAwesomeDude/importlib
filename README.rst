=========
Importlib
=========

This is a backport of Python 3's importlib to Python 2.7. All functionality is
included.

Todo
====

* PEP 3147 compatibility should be restored via a helper module. This should
  be done in a way such that it works on all Python implementations, including
  Python 2 implementations.
* Unit tests are completely broken.
* A switch to zope.interface instead of ABCs could remove the 2.7 dependency
  and make the codebase 2.5-compatible.
