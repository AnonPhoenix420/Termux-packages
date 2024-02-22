apt update --fix-missing
apt upgrade --fix-missing
pkg install nano
pkg install wget 
pkg install tor
pkg install proxychains-ng
pkg install curl
pkg install git
pkg install golang
pkg install ruby
pkg install perl
pkg install python
pkg install python2
pkg install python3
pkg install python-numpy
pkg install python-cryptography
pip install pycryptodome
pkg install tur-repo
pkg install python-pandas
pip3 install pycurl
pip2 install python-geoip
pkg install rust
pip install geoip2
pip install setuptools
pip install setuptools_rust
apt install openssh
pip install beautifulsoup4
pkg install proot
pkg install x11-repo
pkg install php
pip download libsodium
pkg install clang python libffi openssl libsodium
SODIUM_INSTALL=system pip install pynacl
pkg install python-bcrypt
pip install sshmaster
pkg install build-essential autoconf automake git
git clone https://github.com/maxmind/geoip-api-c.git
cd geoip-api-c
git checkout v1.6.12
bash bootstrap
./configure --prefix=$PREFIX
make
make install
