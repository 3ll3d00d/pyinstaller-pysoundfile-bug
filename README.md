Minimal test case for https://github.com/pyinstaller/pyinstaller/issues/4325

To reproduce then clone this repo then

    $ pipenv sync
    $ pyinstaller main.py
    
It should error on any Linux distro but succeed on OSX and Windows, e.g.

    9743 INFO: Loading module hook "hook-soundfile.py"...
    Unable to find "/home/matt/.virtualenvs/beqdesigner-entpycF3/lib/python3.7/site-packages/_soundfile_data" when adding binary and data files.


