Caja extension to add xattrs support on the properties page.

Debug
-----

In order to see caja debug messages, you need to set the CAJA_DEBUG env variable.
e.g.: $ CAJA_DEBUG=y caja

Notes
-----

To test caja-xattrs with a custom caja build you need to specify the
caja-extension dir. e.g.:

$ ./configure --with-cajadir=/usr/local/lib/caja/extensions-2.0/ \
    --prefix=/usr/local
