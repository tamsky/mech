# Contributing to mech 

Anyone can open a pull request to help expand/enhance the functionality are essential to mech's growth.

This guide should help get you started contributing to mech.


## Dev Setup

```sh
# Clone the repo
git clone git@github.com:mkinney/mech.git

# Change into that cloned directory
cd mech

# Create a virtualenv
virtualenv -p python3 venv

# Activate the python virtual environment
source venv/bin/activate

# install mech from this code
python setup.py install

# if doing development
pip install flake8

# also optional
pip install autopep8
# use like this: autopep8 --in-place --aggressive --aggressive somefile.py 

# Configure git to use pre-commit hook
flake8 --install-hook git
```