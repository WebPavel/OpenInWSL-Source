## OpenInWSL-Source

[![CodeQL](https://github.com/Opticos/OpenInWSL-Source/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/Opticos/OpenInWSL-Source/actions/workflows/codeql-analysis.yml)

## Website:
https://opticos.github.io/openinwsl

## Download:

<a href='//www.microsoft.com/store/apps/9ngmqpwcg7sf?cid=storebadge&ocid=badge'><img src='https://developer.microsoft.com/store/badges/images/English_get-it-from-MS.png' alt='English badge' width='200'/></a>

The sourcecode for OpenInWSL

OpenInWSL lets you turn WSL Linux programs into Windows file handlers.

More info and docs coming soon!

## Dependencies (all can be installed with pip)

You can do this in a virtualenv.

```
pygame #Verion 2. The latest.
pywin32
winshell
Pillow
imtools
keyboard
pyinstaller==3.5
pyxdg
psutil
```

Windows 10

```

# open cmd then run the following command
ver
# Microsoft Windows [Version 10.0.19044.3208]
```

Python(3.7.9 is recommended)

[Python 3.7](https://www.python.org/ftp/python/3.7.9/python-3.7.9.exe)

```shell

git config --global http.sslVerify false
git clone https://github.com/Opticos/OpenInWSL-Source.git
pip install -i https://mirrors.ustc.edu.cn/pypi/web/simple pip -U
pip config set global.index-url https://mirrors.ustc.edu.cn/pypi/web/simple
pip install pip_search wheel
pip install pygame pywin32 winshell Pillow imtools keyboard pyinstaller pyxdg psutil
cd OpenInWSL-Source
python .\build.py
```

## Building GWSL

Clone the source from here, install the dependencies with pip, and run ```build.py```.

It will build to ```dist/GWSL_'version'/```.

The official build currently runs on Python 3.7
