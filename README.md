Vcoin integration
================================

Vcoin specs
----------------

Vcoin sha256 POW!
- 50 coins per block
- static const int64 nTargetTimespan = 1200; 
- static const int64 nTargetSpacing = 30; 
- static const int64 nInterval = nTargetTimespan / nTargetSpacing; // 40 blocks
- 1000000000 total coins


License
-------

Vcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the vcoin
development team members simply pulls it.

How to compile vcoind on ubuntu 

- git clone https://github.com/vcoindev/vcoin.git
- cd vcoin 


    cd src; make -f makefile.unix 


 for the GUI compile `cd vcoin`. To compile and run them:
 

    qmake "USE_UPNP=-" vcoin-qt.pro
    make -f Makefile
    ./vcoin-qt
    
    Feel free to contritube

- Contact at vcoindev@gmail.com
- pgp 0x55b27105053d0c23
