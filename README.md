Download and unpack archive to your miner with Claymore.
============================================================
Linux
You can run Hlor daemon with Claymore's Dual Ethereum Miner on Linux in two ways, both local and remote:

1. Local
Run file hlor.sh

./hlor.sh
Enter your username and key, and the desired worker's name.

2. Remote
Open file hlor_remote.sh in your favorite editor and change the IP to your miner's IP. For example, if your have a Windows mining machine with IP 192.168.0.8, your file should look like this:

./hlor --unit claymore --ip 192.168.0.8
Save hlor_remote.sh and run it:

./hlor_remote.sh
Enter your username and key, and the desired worker's name.

============================================================

Windows
To run Hlor daemon with Claymore's Dual Ethereum Miner on Windows:

Run Claymore miner
Run start.bat within the Hlor Addon folder
Provide your Hlor details
Find your Hlor within your profile on Hlor Explorer https://hlor.io/profile
To change your Hlor details edit hlor.conf or just delete it.
