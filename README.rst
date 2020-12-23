========================
Fixing SageMath on macOS
========================

This small module is to help folks install and use SnapPy inside
SageMath, by doing two things:

1) Provide SSL support via openssl so that ``sage -pip install snappy`` works.

2) Install a recent version of Tk so that the SnapPy's graphics work in Sage.

Depending on the version of Sage that you have installed, download one
of ``fix_mac_sage8.tar.gz``, ``fix_mac_sage9.tar.gz`` or ``fix_sage_9_2.tgz`` from::

  http://github.com/3-manifolds/fix_mac_sage/releases/latest/

(Sage 9.2 requires fix_sage_9_2.tgz because it uses Python 3.8 instead of
Python 3.7.  Earlier versions of Sage 9 can use fix_mac_sage9.tgz.)  Unpack
the tar archive, consult the README therein and follow the instructions.
