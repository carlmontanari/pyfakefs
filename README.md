# pyfakefs
pyfakefs implements a fake file system that mocks the Python file system modules.
Using pyfakefs, your tests operate on a fake file system in memory without
touching the real disk.  The software under test requires no modification to
work with pyfakefs.

## Usage
See the [usage tutorial](http://github.com/jmcgeheeiv/pyfakefs/wiki/Tutorial)
for a concrete example of how to apply pyfakefs.

## Continuous Integration

pyfakefs is automatically tested with Python 2.6 and above, and it is currently 
[![Build Status](https://travis-ci.org/jmcgeheeiv/pyfakefs.svg)](https://travis-ci.org/jmcgeheeiv/pyfakefs).

See [Travis-CI](http://travis-ci.org) for
[test results for each Python version](https://travis-ci.org/jmcgeheeiv/pyfakefs).

## Installation

### Compatibility
pyfakefs works with Python 2.6 and above.  pyfakefs requires [mox3](https://pypi.python.org/pypi/mox3).

### PyPi
The pyfakefs on PyPi is unmaintained--many improvements have been made after the PyPi version.  Use the version here.

## History
pyfakefs.py was initially developed at Google by Mike Bland as a modest fake
implementation of core Python modules.  It was introduced to all of Google
in September 2006. Since then, it has been enhanced to extend its
functionality and usefulness.  At Google alone, pyfakefs is used in over 2,000
Python tests.

pyfakefs was released to the public in 2011 as Google Code project
[pyfakefs](http://code.google.com/p/pyfakefs/).

Fork
[jmcgeheeiv-pyfakefs](http://code.google.com/p/jmcgeheeiv-pyfakefs/)
added a [usage tutorial](http://github.com/jmcgeheeiv/pyfakefs/wiki/Tutorial),
direct support for [unittest](http://docs.python.org/2/library/unittest.html)
and [doctest](http://docs.python.org/2/library/doctest.html).

Fork
[shiffdane-jmcgeheeiv-pyfakefs](http://code.google.com/p/shiffdane-jmcgeheeiv-pyfakefs/)
added further corrections.

After the [shutdown of Google Code was announced,](http://google-opensource.blogspot.com/2015/03/farewell-to-google-code.html)
all three Google Code projects are merged together here on GitHub as pyfakefs.

