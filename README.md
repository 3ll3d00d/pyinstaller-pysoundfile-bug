# pyinstaller-pysoundfile-bug

Minimal test case for https://github.com/pyinstaller/pyinstaller/issues/4325

To reproduce then clone this repo then

    $ pipenv sync
    $ pyinstaller main.py
    
It should error on any Linux distro but succeed on OSX and Windows

