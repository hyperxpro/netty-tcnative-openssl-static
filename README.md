# Netty Tcnative OpenSSL Static
This repository generates [Netty Tcnative](https://github.com/netty/netty-tcnative) `openssl-static` static builds. Netty itself does not release `openssl-static` builds, but only `boringssl-static`.
However, some of us require OpenSSL build, not BoringSSL build. This repository is created to bridge that gap.

Build specs:
- Debian 12
- Java 8 (Amazon Corretto)
- CMake 3.25.1
- gcc 12.2.0
