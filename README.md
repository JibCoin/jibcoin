Jibcoin integration/staging tree
================================

http://www.jibcoin.org

Copyright (c) 2009-2018 Bitcoin Developers
Copyright (c) 2018 Jibcoin Developer

What is Jibcoin?
----------------

Jibcoin is a modified version of Litecoin. 

License
-------

Jibcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
 

### Testing

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./jibcoin-qt_test

