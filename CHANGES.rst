What's New on LIAC-ARFF
=======================

LIAC-ARFF NEXT
--------------



LIAC-ARFF 2.1.0
---------------

- fix: working for 2.6+
- fix: working for 3.3+
- new: encoder checks if data has all attributes
- new: sparse data support


LIAC-ARFF 2.0.2
---------------

- fix: attribute and relation names now follow the new ARFF specification.
- new: encoded nominal values.


LIAC-ARFF 2.0.1
---------------

- fix: dump now escapes correctly special symbols, such %, ', ", and \.


LIAC-ARFF 2.0
-------------

- new: ArffEncoder and ArffDecoder helpers which actually do the serialization
  and loading of ARFF files.
- new: UnitTest cases for all classes and functions.
- new: Detailed exceptions for many cases.
- fix: load, loads, dump, dumps are now simpler.
- rem: arfftools.py and the split function.


LIAC-ARFF 1.0
-------------

First commit.

- new: load, loads, dump, dumps functions
