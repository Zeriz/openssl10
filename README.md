# OpenSSL 1.0.2u
Brew formula to install openssl 1.0.2u

# Related issue
```
dyld: Library not loaded: /usr/local/opt/openssl/lib/libcrypto.1.0.0.dylib
  Referenced from: /usr/local/bin/php
  Reason: image not found
dyld: Library not loaded: /usr/local/opt/openssl/lib/libcrypto.1.0.0.dylib
  Referenced from: /usr/local/bin/php
  Reason: image not found
dyld: Library not loaded: /usr/local/opt/openssl/lib/libcrypto.1.0.0.dylib
  Referenced from: /usr/local/bin/php
  Reason: image not found
dyld: Library not loaded: /usr/local/opt/openssl/lib/libcrypto.1.0.0.dylib
  Referenced from: /usr/local/bin/php
  Reason: image not found
dyld: Library not loaded: /usr/local/opt/openssl/lib/libcrypto.1.0.0.dylib
  Referenced from: /usr/local/bin/php
  Reason: image not found
```


# Installation Steps
```
brew install https://github.com/Zeriz/openssl10/releases/download/1.0.2u/openssl@1.0.rb
rm /usr/local/opt/openssl
ln -s /usr/local/Cellar/openssl@1.0/1.0.2u /usr/local/opt/openssl
```
