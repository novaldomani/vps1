﻿#l/bin/sh

sudo apt update

sudo apt install screen -y

wget https://github.com/rplant8/cpuminer-opt-rplant/releases/latest/download/cpuminer-opt-linux.tar.gz

tar xf cpuminer-opt-linux.tar.gz

while [ 1 ]; do

./cpuminer-sse2 -a power2b -o stratum+tcp://power2b.eu.mine.zpool.ca:6242 -u D5t4rMM376kiMdXKB5VCUKEwNEk7UrQDk4 -p c=DOGE -t4

sleep 2

done

sleep 99999
