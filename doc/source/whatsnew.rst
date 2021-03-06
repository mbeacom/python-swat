
.. Copyright SAS Institute

.. _whatsnew:

**********
What's New
**********

This document outlines features and improvements from each release.

v1.2.1 (September 13, 2017)
===========================

- Better support for binary data in table uploads and parameters
- Add integer missing value support
- Allow list parameters to also be sets
- Improve connection protocol detection
- Add ``eval`` method to ``CASTable``

v1.2.0 (May 2, 2017)
====================

- Use ``upload`` action rather than ``addtable`` for ``read_*`` methods.
- Add basic Zeppelin notebook support (``from swat.notebook.zeppelin import show``)

v1.1.0 (March 21, 2017)
=======================

- Add support for Python 3.6 (Linux extension)
- Implement ``sample`` method on ``CASTable``
- Add sampling support to plotting methods
- ``cas.dataset.max_rows_fetched`` increased to 10,000
- Add ``terminate`` method to ``CAS`` object to end session and close connection
- Implement ``fillna``, ``replace``, and ``dropna`` methods on ``CASTable``
- Add ``apply_labels`` method on ``SASDataFrame`` to set column labels as column names

v1.0.0 (September 9, 2016)
==========================

- Initial Release
