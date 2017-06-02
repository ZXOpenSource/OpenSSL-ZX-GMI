*********************************************************************************************************** 
OpenSSL-ZX-GMI 
===================================
1. based on OpenSSL
2. include evp framework of China's Algorithm SM3 and SM4
3. implement Zhaoxin GMI support as a engines. GMI can be used to speed up the SM3 and SM4.
  

第一次release：
-----------------------------------
### openssl-1.1.0-pre5-ZX-GMI-1.0.tar.gz
1. based on openssl 1.1.0-pre5
2. the ZX-GMI engine code is in version 1.0
3. example to show how to build. 
(1) ./config --prefix= \<install path\> no-shared
(2) make update
(3) make
(4) make install

### openssl-1.0.2h-ZX-GMI-1.0.tar.gz
1. based on openssl 1.0.2h
2. the ZX-GMI engine code is in version 1.0
3. example to show how to build. 
(1) ./config --prefix= \<install path\> no-shared
(2) touch crypto/objects/objects.txt 
(3) make
(4) make install
  

第二次release：
-----------------------------------
由于openssl存在重大安全更新，因此，OpenSSL-ZX-GMI也随之做了相应的更新。以上两个版本更新后对应到如下两个版本openssl-1.1.0b-ZX-GMI.tar.gz和openssl-1.0.2j-ZX-GMI-1.0.tar.gz
### openssl-1.1.0b-ZX-GMI-1.0.tar.gz
1. based on openssl 1.1.0b
2. the ZX-GMI engine code is in version 1.0
3. example to show how to build. 
(1) ./config --prefix=\<install path\> no-shared
(2) make update
(3) make
(4) make install

### openssl-1.0.2j-ZX-GMI-1.0.tar.gz
1. based on openssl 1.0.2j
2. the ZX-GMI engine code is in version 1.0
3. example to show how to build. 
(1) ./config --prefix=\<install path\> no-shared
(2) touch crypto/objects/objects.txt 
(3) make
(4) make install

## GMI update：    
### openssl-1.1.0-pre5-ZX-GMI-1.0.tar.gz
1. based on openssl-1.1.0-pre5-ZX-GMI-1.0.tar.gz
2. the ZX-GMI engine code is in version 1.1. Fix sm4-cbc bug.
3. example to show how to build. 
(1) ./config --prefix=\<install path\> no-shared
(2) make update
(3) make
(4) make install

### openssl-1.1.0b-ZX-GMI-1.1.tar.gz
1. based on openssl-1.1.0b-ZX-GMI-1.0.tar.gz
2. the ZX-GMI engine code is in version 1.1. Fix "make update" failure issue.
3. example to show how to build. 
(1) ./config --prefix=\<install path\> no-shared
(2) make update
(3) make
(4) make install
  

第三次release：
-----------------------------------
由于openssl存在安全更新，因此，OpenSSL-ZX-GMI也随之做了相应的更新。
### openssl-1.1.0e-ZX-GMI-1.1.tar.gz
1. based on openssl-1.1.0e.tar.gz
2. the ZX-GMI engine code is in version 1.0. 
3. example to show how to build. 
(1) ./config --prefix=\<install path\> no-shared
(2) make update
(3) make
(4) make install
