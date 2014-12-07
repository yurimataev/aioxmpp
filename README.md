``asyncio_xmpp``
================

... is a pure-python XMPP library using the new [``asyncio``][0] standard library
module from Python 3.4 (and
[available as a third-party module to Python 3.3][1]).

Dependencies
------------

* Python ≥ 3.4 (or Python = 3.3 with tulip and enum34)
* DNSPython

Known problems
--------------

* DANE support is very limited. This is due to some limitations of PyOpenSSL or
  my ability to find the correct functions in the (Py-)OpenSSL documentation...

Design goals
------------

* Powerful API to implement all sorts of XEPs
* Reliable message transmission even under dire network circumstances
* Well-tested code base
* A more compelling README than this

   [0]: https://docs.python.org/3/library/asyncio.html
   [1]: https://code.google.com/p/tulip/
