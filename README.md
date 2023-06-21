CHidentifier is a pun on Chirality Identifier. CHIdentifier is an easy-to-use command line program to determine if two molecular systems are chiral to each other and if one is an enantiomer of the other. The chirality is resolved within a tolerance value defined by the user. CHIdentifier requires three input parameters, the first two are the file names of each of the molecules to be tested, while the third is an optional tolerance (TOL) parameter. The format of the input molecules is required to be XYZ. CHIdentifier can generate sample files from a menu, depending on the chosen case, to facilitate the dynamics of use. The program outputs a binary answer in each case: 1 if the compared molecules are enantiomers and 0 otherwise.

Installing CHidentifier
===============

You can install and uninstall with:

```
# install
pip3 install chidentifier

# invoque as:
x.chidentifier.py

# uninstall
pip3 uninstall chidentifier
```

or

```
# install
git clone https://github.com/fortizchi/chidentifier
cd chidentifier/dist/
python3 -m pip install   chidentifier-0.1-py3-none-any.whl --upgrade --no-cache-dir

# invoque as:
x.chidentifier.py

# uninstall: in chidentifier/dist/
python3 -m pip uninstall chidentifier-0.1-py3-none-any.whl
```

Running CHidentifier
===============

```
x.chidentifier.py
```
