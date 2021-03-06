Superblocks - Version 0.4.3
===========================

A collection of programs to determine the Next Block Reward for
cryptocurrencies with superblocks and/or variable reward blocks.

Discussions: https://bitcointalk.org/index.php?topic=264740.0

Files:

* README.md - This file!
* TODO - To do list for Superblocks project

* makefile - Makefile to create all these fun little programs

* test-next.sh - Test script to test these fun little programs

* superblocks.hpp - Superblocks class and includes
* utils.cpp - Mersenne Twister random, hex2long, etc

* next.cpp - Get Next Block Reward controller 
* precom.cpp - Precompute lucky hash cutouts controller

* set-cdc.cpp - Reward settings for [CDC] Cloudcoin 
* set-elp.cpp - Reward settings for [ELP] Elephantcoin
* set-gil.cpp - Reward settings for [GIL] Gil
* set-grw.cpp - Reward settings for [GRW] Growthcoin 
* set-lky.cpp - Reward settings for [LKY] Luckycoin
* set-nug.cpp - Reward settings for [NUG] Nuggets
* set-red.cpp - Reward settings for [RED] Redcoin   
* set-spt.cpp - Reward settings for [SPT] Spots
* set-str.cpp - Reward settings for [STR] Starcoin 

* list-jkc.cpp - Generate list of all superblocks for [JKC] Junkcoin
* list-sxc.cpp - Generate list of all superblocks for [SXC] Sexcoin
* rewardlists/rewardlist.jkc.txt - List of JKC superblocks up to block 100,000
* rewardlists/rewardlist.sxc.txt - List of SXC superblocks up to block 100,000



Coins
=====

Superblock Coins that seed with Block Height:
* JNK - Junkcoin - https://github.com/Hartland/JKC
* SXC - Sexcoin - https://github.com/sexcoin-project/sexcoin

Superblock/Variable Reward Coins that seed with the Previous Block Hash:
* CDC - Cloudcoin - (no repo)
* DMD - DiamondCoin - https://github.com/diamondcoinproject/diamondcoin
* ELP - ElephantCoin - https://github.com/elephantcoin/elephantcoin
* GDC - Grandcoin - https://github.com/grandcoin/grandcoin
* GIL - Gil (variable) - https://github.com/hydroponica/gil  
* GRW - Growthcoin - https://github.com/growthcoinproject/growthcoin
* LKY - Luckycoin - https://github.com/LuckyCoinProject/Luckycoin
* NUG - Nuggets - https://bitbucket.org/mytwobits/nuggets
* PHS - Philosopherstone - https://github.com/philosopherstonecoin/philosopherstone
* RED - Redcoin (+variable)- https://github.com/redcoinproject/redcoin/
* SPT - Spots - https://github.com/spots-project/spots
* STR - Starcoin - https://github.com/starcoinproject/starcoin

Coins that seed with Current Block Hash, or other methods:
* ?

Donate
======

Donate? More Code? Donate! More Fun!

* BTC: 16SUC5BXqRrLJc4X8FY8DA1hRyMexDvjfZ
* LTC: LQfRTHVMv66PZQkgJPXRVB5TeBiw52eKtZ
* NMC: N21qPigWkowtq9K2Q4rhRgAcACkhvgvdRw
* CDC: BxZkn1EK1JMzPJprnaXjJYMwRbK86gPeeG
* DMD: dJrkor1TjfZBuccKL1WorSWW5NYYucYQkA
* ELP: e7Xxn4c3A2UwYUtVNrBSph45LP4SLCSf1w
* GDC: g8Dyhc6UhvoKdeavVwr3FKR1UuM9tm4cfW
* GIL: 78WWxherV8oUa79pVYXuV36VsYDobxJTU7
* GRW: GPHPcCWUpHTdP5Mp4CCEdvMbM99VzBvNe6
* JNK: 7Xr7wox9CKGMPYHuWxsDyANHW3UkMgViUm
* LKY: L1KpUBC5CudWjycbGyC713og1gTzP4o9qi
* NUG: NRMSNpyoTzQmeaT7RVC1uoSPni1ebEV99m
* PHS: 9YY8sMSakDajUhzLe4XpPnjDeZmTt5iXMV
* RED: Re4GFhN79S7nC3ZocqrZnocgpk5CJ5nf3E
* SPT: MDLdRW5wLT29CH2rMEC4TRd2uCEpScjNZE
* STR: sPgsGeSYaymrXnVMBhAxpq3372ZZriJ6Gs
* SXC: S3PsEofPrcaf1UhteGBtGvtUTFL93CEYqm
* Hash160: 3BA9B9CCDFF4B1CC65AB2E9D095A8C6EB9E1E09F


Open Source
===========

Copyright (c) 2013 Superblock Developers

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

