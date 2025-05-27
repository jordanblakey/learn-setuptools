# learn-setuptools

https://test.pypi.org/project/learn-setuptools-pLm9yZ/0.0.10/

```sh
# install deps
python -m venv .venv
python -m pip install --upgrade pip
pip install wheel

# build binary distribution
python setup.py bdist_wheel
# build source distribution
python setup.py sdist
# install locally
pip install . --use-pep517
# install using named extras dependency group -- this installs twine
pip install .[dev] --use-pep517

# check build files
twine check dist/*

```
