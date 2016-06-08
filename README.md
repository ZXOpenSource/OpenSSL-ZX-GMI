# OpenSSL-ZX-GMI
1. based on OpenSSL
2. include evp framework of China's Algorithm SM3 and SM4
3. implement Zhaoxin GMI support as a engines. GMI can be used to speed up the SM3 and SM4.


#openssl-1.1.0-pre5-ZX-GMI-1.0.tar.gz
1. based on openssl 1.1.0-pre5
2. the ZX-GMI engine code is in version 1.0
3. example to show how to build. 
    (1) ./config --prefix=<install path> no-shared
    (2) make update
    (3) make
    (4) make install

#openssl-1.0.2h-ZX-GMI-1.0.tar.gz
1. based on openssl 1.0.2h
2. the ZX-GMI engine code is in version 1.0
3. example to show how to build. 
    (1) ./config --prefix=<install path> no-shared
    (2) make
    (3) make install


