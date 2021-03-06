***************
Release History
***************

.. Changelog entries should follow this format:

   version (release date)
   ======================

   **section**

   - One-line description of change (link to Github issue/PR)

.. Changes should be organized in one of several sections:

   - Added
   - Changed
   - Deprecated
   - Removed
   - Fixed

0.2.1 (unreleased)
==================



0.2.0 (2018-02-06)
==================

**Fixed**

- Fixed tests to work with ``pytest>=3.3``. Pytest added progress indicators
  to test output in version 3.3, which the tests were not expecting.

0.1.1 (2016-03-07)
==================

**Added**

- Added the ``--shell`` command line option and now checks the ``CRAMSHELL``
  environment variable to override the default ``/bin/sh`` shell.
  (`#3 <https://github.com/tbekolay/pytest-cram/pull/3>`_)

  Thanks to `Florian Rathgeber <https://github.com/kynan>`_ for the contribution!

**Changed**

- Depend explicitly on ``cram>=0.7``. If you would like support for earlier
  versions of cram, please
  `file an issue <https://github.com/tbekolay/pytest-cram/issues/new>`_.

0.1.0 (2016-02-28)
==================

Initial release of ``pytest-cram``! Supports Python 2.7+ and 3.3+.
