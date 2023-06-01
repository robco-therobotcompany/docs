librobcomm
==========

``librobcomm`` is a C++ library for communicating with Robco robots.

.. _librobcomm-install:

Installation
------------

``librobcomm`` can be installed by building from source, then installing the
generated Debian package. Clone the
`repository <https://github.com/robco-therobotcompany/librobcomm>`_, then execute
the following commands::

    ~/librobcomm$ rm -rf ./build
    ~/librobcomm$ mkdir -p build
    ~/librobcomm$ cd build
    ~/librobcomm/build$ cmake ..
    ~/librobcomm/build$ make
    ~/librobcomm/build$ cpack
    ~/librobcomm/build$ sudo apt install ./librobcomm*.deb

