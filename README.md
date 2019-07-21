Minimal test case for https://github.com/pyinstaller/pyinstaller/issues/4325

To reproduce then clone this repo then

    $ pipenv sync
    $ pyinstaller main.py
    
It should error on any Linux distro or on OSX but succeed on Windows
