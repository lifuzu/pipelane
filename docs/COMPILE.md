<!-- COMPILE.md -->

### Steps

```
$ pip install --user --upgrade setuptools wheel
```

```
$ python setup.py sdist bdist_wheel
```

```
$ pip install --user --upgrade twine
```

```
$ twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```

```
$ pip install --index-url https://test.pypi.org/simple/ pipelane
```

### References
https://packaging.python.org/tutorials/packaging-projects/