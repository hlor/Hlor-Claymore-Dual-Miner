# Hlor-Addon-Claymore-Dual-Miner
<strong>Hlor Addon Claymore Dual Ethereum AMD+NVIDIA GPU Miner</strong>

<strong>Claymore's Dual Ethereum Miner v11.9</strong> is one of the most popular Ethereum dual miner for AMD and Nvidia GPUs.
It comes with two new algorithms that can be used in dual mining mode along with Ethereum or any other Ethash-based coin, these are Blake2s and Keccak. It provides stability and high performance to get maximum from modern GPUs (GPU and NVIDIA).

<strong>FEATURES:</strong>

- Supports new "dual mining" mode: mining both Ethereum and Decred/Siacoin/Lbry/Pascal at the same time, with no impact on Ethereum mining speed. Ethereum-only mining mode is supported as well.
- Effective Ethereum mining speed is higher by 3-5% because of a completely different miner code - much less invalid and outdated shares, higher GPU load, optimized OpenCL code, optimized assembler kernels.
- Supports both AMD and nVidia cards, even mixed.
- No DAG files.
- Supports all Stratum versions for Ethereum: can be used directly without any proxies with all pools that support eth-proxy, qtminer or miner-proxy.
- Supports Ethereum and Siacoin solo mining.
- Supports both HTTP and Stratum for Decred.
- Supports both HTTP and Stratum for Siacoin.
- Supports Stratum for Lbry, Pascal, Blake2s, Keccak.
- Supports failover.
- Displays detailed mining information and hashrate for every card.
- Supports remote monitoring and management.
- Supports GPU selection, built-in GPU overclocking features and temperature management.
- Supports Ethereum forks (Expanse, etc).
- Windows and Linux versions.


<strong>Claymore's Configuration File:</strong>

You can use "config.txt" file instead of specifying options in command line. 
If there are not any command line options, miner will check "config.txt" file for options.
If there is only one option in the command line, it must be configuration file name.
If there are two or more options in the command line, miner will take all options from the command line, not from configuration file.
Place one option per line, if first character of a line is ";" or "#", this line will be ignored. 


This miner is free-to-use, however, current developer fee is 1% for Ethereum-only mining mode (-mode 1) and 1.5% for dual mining mode (-mode 0), every hour the miner mines for 36 or 54 seconds for developer. 
For all 2GB cards and 3GB cards in Windows10 (they cannot mine ETH/ETC anymore) devfee is 0%, so on these cards you can mine all ETH forks without devfee, this miner is completely free in this case.
If some cards are 2GB and some >2GB, 2GB cards still mine for you during devfee time, only cards that have more than 2GB memory will be used for devfee mining. Same for 3GB cards in Windows10. Miner displays appropriate messages during startup.
Second coin (Decred/Siacoin/Lbry/Pascal/Blake2s/Keccak) is mined without developer fee.
So the developer fee is 0...1.5%, if you don't agree with the dev fee - don't use this miner, or use "-nofee" option.
Attempts to cheat and remove dev fee will cause a bit slower mining speed (same as "-nofee 1") though miner will show same hashrate. 
Miner cannot just stop if cheat is detected because creators of cheats would know that the cheat does not work and they would find new tricks. If miner does not show any errors or slowdowns, they are happy.

This version is for recent AMD videocards only: 7xxx, 2xx and 3xx, 2GB or more. Recent nVidia videocards are supported as well.
There are builds for Windows x64 and for Linux x64 (tested on Ubuntu 14.04). No 32-bit support. 


<strong>DEVELOPER'S LINKS:</strong>

MEGA: <a href="https://mega.nz/#F!O4YA2JgD!n2b4iSHQDruEsYUvTQP5_w" rel="nofollow" target="blank">https://mega.nz/#F!O4YA2JgD!n2b4iSHQDruEsYUvTQP5_w</a> <br />
GOOGLE: <a href="https://drive.google.com/open?id=0B69wv2iqszefdFZUV2toUG5HdlU" rel="nofollow" target="blank">https://drive.google.com/open?id=0B69wv2iqszefdFZUV2toUG5HdlU</a> 

For more information check the official BitcoinTalk post: <br />
https://bitcointalk.org/index.php?topic=1433925.0
