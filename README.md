python-latex
============

parsing and modifying LaTeX documents with python

![build status](https://secure.travis-ci.org/omnidan/python-latex.png?branch=master)


Installation
------------

To install python-latex, simply run (as root):
`python setup.py install`

On Debian you would run this as root by running:
`su -c "python setup.py install"`

And on Ubuntu:
`sudo python setup.py install`


Usage
-----

To use my scripts built with python-latex, you can (after installing python-latex) run any python script in the `scripts/` directory.

To run LatexBeautifier: `python scripts/LatexBeautifier.py`

To run LatexRefactor: `python scripts/LatexRefactor.py`


Hacking
-------

In your python script, you can now import objects from latex: `from latex import LatexParser`

Most functions are documented using python docstrings.
