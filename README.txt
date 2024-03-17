Fixing Termux Errors & Install Command Setup

apt update --fix-missing
apt upgrade --fix-missing

( next setup termux storage )

termux-setup-storage

( creat a directory called termux )

mkdir termux

( open termux directory )

cd termux

( install the commands bellow )


pkg i cmake
pkg i nano
pkg i wget 
pkg i tor
pkg i proxychains-ng
pkg i curl
pkg i cloudflared
pkg i subversion
pkg i python
pkg i python2
pkg i python3
pkg i perl
pkg i ruby
pkg i golang
pkg i python-numpy
pkg i tur-repo
pkg install root-repo
pkg install x11-repo
pkg i python-pandas
pkg i python-cryptography
pkg i python-bcrypt
apt install openssh
pkg i proot
pkg i php
pkg i rust
pkg i tor
pkg i proxychains-ng
pkg i nmap

pip install slowloris
pip2 install python-ping


apt install pycurl 


**   pip install pycurl   ****
( this worked for me after fixing the other python termux issues )

Or

sudo apt install pycurl 
(for root only)

pip2 install python-geoip
pip install geoip2

( I recommend doing this B4 further upgrading pip2 )


pkg install clang python libffi openssl libsodium

SODIUM_INSTALL=system pip install pynacl


pip install clang
pip2 install clang
pip2 install pycrypto
pip3 install clang
pip install setuptools
pip install beautifulsoup4
pip install sshmaster
pip install setuptools_rust



***Instillation for numpy module**

pkg install python build-essential cmake ninja libopenblas libandroid-execinfo

pip3 install setuptools wheel packaging pyproject_metadata cython

MATHLIB=m pip3 install --no-build-isolation numpy




**If you cannot install PyCrypto**

( For termux you can simply go to )

/usr/include/python3.11


( type the following )

cd /data/data/com.termux/files/usr/include/python3.11


( Show this path with pwd )


( open cpython copy longintrepr.h to the python3.11 path )

cd cpython 

cp longintrepr.h /data/data/com.termux/files/usr/include/python3.11


( make sure you have clang for pip3 )


pip3 install clang


( Then type )


pip3 install pycrypto

