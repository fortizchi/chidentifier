chidentifier stands for Ultrafast shape-recognition algorithm with mass ponderation. chidentifier is an easy-to-use program to discriminate similar molecules in a list. The chidentifier program requires a list of concatenated molecules in XYZ format and an optional tolerance parameter as input parameters. The input file name can be anything if it contains at least two joined molecules in XYZ format. If you don't have a valid xyz file, chidentifier can create a sample file as appropriate.

Installing chidentifier
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

Running chidentifier
===============

```
x.chidentifier.py
```
