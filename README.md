# AfterEther cryptocurrency project

AfterEther is a project to create a copy of Ether (ETH), the currency of Ethereum.

http://afterether.org


## Patches for Ethereum releases

This repository contains patches that have to be applied to Ethereum source code
to convert it to AfterEther source code.

## To apply a patch

    cd go-ethereum-X.Y.Z
    patch -p1 < go-afterether-vX.Y.Z.diff
