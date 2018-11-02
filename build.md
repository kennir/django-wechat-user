# build dist
`python3 setup.py sdist bdist_wheel`

# upload to pypi
`twine upload dist/* -r testpypi`
`twine upload dist/* -r pypi`

# password
`Mcmd9R3y3GTuZXX`

# .pypirc
```ini
[distutils]
index-servers =
        testpypi
        pypi

[testpypi]
username: kennir
password: Mcmd9R3y3GTuZXX

[pypi]
username: kennir
password: Mcmd9R3y3GTuZXX
```