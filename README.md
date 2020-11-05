# Please Read
Pyrit is new, is outdated and it's still Python2 I am currently attempting to rewrite it from scratch, so thanks for all the stars but remember to keep an eye for Python3 version.

# Pyrit
The famous WPA precomputed cracker, Migrated from Google
Fixed Fluxion Error Pyrit missing.
![pyrit logo](https://github.com/anonymousproo/Pyrit/blob/main/Pyrit.png)

Pyrit allows you to create massive databases of pre-computed WPA/WPA2-PSK authentication phase in a space-time-tradeoff. By using the computational power of Multi-Core CPUs and other platforms through ATI-Stream,Nvidia CUDA and OpenCL, it is currently by far the most powerful attack against one of the world's most used security-protocols.

WPA/WPA2-PSK is a subset of IEEE 802.11 WPA/WPA2 that skips the complex task of key distribution and client authentication by assigning every participating party the same pre shared key. This master key is derived from a password which the administrating user has to pre-configure e.g. on his laptop and the Access Point. When the laptop creates a connection to the Access Point, a new session key is derived from the master key to encrypt and authenticate following traffic. The "shortcut" of using a single master key instead of per-user keys eases deployment of WPA/WPA2-protected networks for home- and small-office-use at the cost of making the protocol vulnerable to brute-force-attacks against it's key negotiation phase; it allows to ultimately reveal the password that protects the network. This vulnerability has to be considered exceptionally disastrous as the protocol allows much of the key derivation to be pre-computed, making simple brute-force-attacks even more alluring to the attacker

Pyrit is free software - free as in freedom. Everyone can inspect, copy or modify it and share derived work under the GNU General Public License v3+. It compiles and executes on a wide variety of platforms including FreeBSD, MacOS X and Linux as operation-system and x86-, alpha-, arm-, hppa-, mips-, powerpc-, s390 and sparc-processors.

# What's new

    Fixed #479 and #481
    Pyrit CUDA now compiles in OSX with Toolkit 8.5
    Added use_CUDA and use_OpenCL in config file
    Improved cores listing and managing
    limit_ncpus now disables all CPUs when set to value <= 0
    Improve CCMP packet identification, thanks to yannayl

See CHANGELOG file for a better description.

# How to use 

open terminal 

apt-get install libpcap-dev<br>
apt-get install python2.7-dev libssl-dev zlib1g-dev libpcap-dev<br>
git clone https://github.com/anonymousproo/Pyrit<br>
after Installation complete  Pyrit<br>
cd pyrit<br>
python setup.py clean<br>
python setup.py build<br>
python setup.py install<br>

# How to participate

youtube.com/anonymousproo
