venvdiff
========

Takes 2 requirements.txt (for python virtualenvs) and shows the diff between the installed packages.

### Usage

To compare two requirements files:
`python venvdiff.py requirements1.txt requirements2.txt`

To compare the active virtualenv with a requirements file:
`pip freeze | python venvdiff.py - requirements.txt`
