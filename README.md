pkg install upgrade

apt install git

apt install wget

apt install proot

termux-setup-storage

git clone https://github.com/Neo-Oli/termux-ubuntu

cd termux-ubuntu

chmod +x ubuntu.sh (optional)

sh ubuntu.sh (optional)

./start-ubuntu.sh (optional)


apt update

apt upgrade

Install cmake

git clone https://github.com/xmrig/xmrig

cd xmrig

mkdir build

cd build

cmake -DWITH_HWLOC=OFF ..

make


Then RUN THE MINER

./xmrig -o xmr-asia1.nanopool.org:14433 -u Your_84YUAQKYV6HKpM89Q8MVr48b1ueFmw14gb6ohFFqkUoQQk3g1UBbhaV8ehdMxTengPYoUY3Qtpje8UPBdnGwgCCu8pkkkn4 --tls --coin monero
