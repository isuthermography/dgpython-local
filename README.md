dgpython-local
==============

dgpython-local is a placeholder package that is intended so you
can make your own private branches with dataguzzler-python
configuration local to your organization, laboratory, or system.

Be sure to set local_identifier in setup.py to something that
clearly identifies your organization or laboratory. It may
contain ASCII characters a-z and A-Z and digits 0-9 and
periods.

The example dgpython_local/local.dpi illustrates how you can
provide local functionality when available that might vary
between computers. 

Basic requirements are Python v3.8 or above with the following packages: numpy, setuptools, wheel, build, setuptools_scm

Basic installation is (possibly as root or Administrator):
    pip install --no-deps --no-build-isolation .


