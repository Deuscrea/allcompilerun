how to tx wif to hex hex to wif bitcoin

from 

https://github.com/matja/bitcoin-tool

prepare

from site bitcoin-tool


    A C compiler
    OpenSSL headers and libraries (with elliptic curve support)
    GNU make : Packages: FreeBSD gmake
    GNU bash (for running tests)
    xxd (for running tests) : Packages: Linux vim, FreeBSD vim or vim-lite
    
sudo apt install gcc
sudo apt install g++
//openssl (sudo -s su root if get some error)
sudo apt update && apt install build-essential checkinstall zlib1g-dev libtemplate-perl
sudo apt-get install libssl-dev
sudo apt-get install -y xxd

sudo apt-get update

***sudo apt-file find openssl/err.h
***sudo apt-get install libssl-dev

https://www.youtube.com/watch?v=_KznkWyNCMk

https://github.com/ELHARAKA/MassPrivatekeysToWIF

sudo apt-get install python

git clone https://github.com/ELHARAKA/MassPrivatekeysToWIF.git

cd MassPrivatekeysToWIF

chmod +x pvkmassconvert_compressed.py

0000000000000000000000000000000000000000000000000000000000000001

to file text

python pvkmassconvert_compressed.py

./bitcoin-tool --input-type private-key-wif --input-format base58check --output-type private-key --output-format hex --network bitcoin  --input "KwDiBf89QgGbjEhKnhXJuH7LrciVrZi3qYjgd9M7rFU73sVHnoWn"

0000000000000000000000000000000000000000000000000000000000000001


