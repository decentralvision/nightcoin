# Nightcoin development tree

TO build use

Build with:  make -j4 -f makefile.unix RELEASE=1

Nightcoin is a hybrid PoW/PoS-based cryptocurrency with masternodes.

## PoW
* Algorithm: Scrypt
* PoW Supply: unlimited
* PoW Spacing: 30 Seconds
* PoW Interval: 5 blocks 
* PoW Reward:
    * &le; block 50: 5 NTC
    * &le; block 555: 1055 NTC
    * &le; block 1555: 55 NTC
    * forever:  5 NTC

## PoS
* PoS Reward:
    * 3 QUAN to masternodes
    * 2 QUAN to staking
* PoS Minimum Age: 24 hours
* PoS Maximum Age: none

## Masternodes
* Masternode Collateral: 5000 NTC
* Masternode Enable:  block #1000, approximately

## Ports
* P2P Port: 5050
* RPC Port: 5051
