
## Prerequisite

In order to build hifircd, the following dependencies need to be installed.
Sample commands are given for Arch based distros.

### drogon

* `aurman -S drogon`

### jsoncpp

* `pacman -S jsoncpp`

### uuid

* `aurman -S jsoncpp`

### openssl

* `pacman -S openssl`

### zlib

* `pacman -S zlib`


## Build

`mkdir build && cd build && cmake .. && make`
