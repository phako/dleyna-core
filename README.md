Introduction:
-------------

TODO

Compilation
------------

TODO

Working with the source code repository
---------------------------------------

dleyna-core can be downloaded, compiled and installed as
follows:

   Clone repository
```
     # git clone https://github.com/phako/dleyna-core.git
     # cd dleyna-core
```
   Configure and build
```
     # meson setup build
     # ninja -C build
```

   Final installation
```
     # sudo ninja -C build install
 ```

Configure Options:
------------------

`-Dlog_level`

See logging.txt for more information about logging.
