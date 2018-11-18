# Get start to connect with AWS remotely

### Install AWS Command Line Interface (CLI)
```
pip install awscli --upgrade --user
```
* Update pip if needed
```
python -m pip install --upgrade pip
```
* Result
```
Successfully installed awscli-1.16.57 botocore-1.12.47
```

### Verify installation
```
aws --version
```

### Issues
* File association not found for extension .py
* Solution:
```
assoc .py=py_auto_file
ftype py_auto_file="C:\Python\Python36-32\python.exe" "%1" %*
```
* References:
[Error: File association not found for extension .py](https://secretweaponsdigital.wordpress.com/2015/07/23/error-file-association-not-found-for-extension-py/)
