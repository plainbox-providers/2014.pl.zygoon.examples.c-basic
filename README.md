A tiny PlainBox provider using C
================================

Usage instructions (Ubuntu 14.04) *with plainbox 0.5.2 (0.5.1 won't work)*:
```
    sudo apt-get install plainbox
    sudo apt-get install gcc
    ./manage.py build
    ./manage.py info
    ./manage.py develop # (good for hacking, see manage.py install for packaging)
    plainbox run -i 2014.pl.zygoon.examples.c::hello-world
```

Also look at: http://plainbox.readthedocs.org/en/latest/author/providers.html
