pip install setuptools
pip install twine
python setup.py sdist
PYTHONIOENCODING=utf-8 twine upload --repository-url https://upload.pypi.org/legacy/ dist/theanswre-0.2.5.tar.gz