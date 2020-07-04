========================
Fixing SageMath on macOS
========================

This small module is to help folks install and use SnapPy inside
SageMath, by doing two things:

1) Provide SSL support via openssl so that `sage -pip install snappy`
   works.

2) Install a recent version of Tk so that the SnapPy's graphics work
   in Sage.

To install, download the either "fix_mac_sage8.tar.gz" or
"fix_mac_sage9.tar.gz", from::

  http://github.com/3-manifolds/fix_mac_sage/releases/latest/

depending on whether you have SageMath 8.* or 9.*, unpack, consult the
README therein and follow the instructions
