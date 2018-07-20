## Build Documentation:



#### Install Requirements

```python
pip install -r docs/requirements.txt
```



#### Build Documentation

```python
# Enter docs folder.
cd docs
# Use sphinx autodoc to generate rst.
sphinx-autodoc -o source/ ../matchzoo/
# Generate html from rst
make clean
make html
```

