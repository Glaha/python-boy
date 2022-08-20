# python installation in windows

## Download python embedded version

https://www.python.org/ftp/python/3.10.6/python-3.10.6-embed-amd64.zip

## Add path to env

## Install pip

```shell
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
vi pythonXXX._pth #uncomment #import site
# add Scripts file to path
pip list # check install succeed
pip install flake8
pip install yapf
# install vscode
# install extensions python
# create workspace and add settings
{
    "python.linting.flake8Enabled": true,
    "python.formatting.provider": "yapf",
    "python.linting.flake8Args": ["--max-line-length=248"],
    "python.linting.pylintEnabled": false
}
# create hello.py and F5 to run
```

