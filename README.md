# ledger-app-csc
CSC wallet application for Ledger Blue and Nano S

## Introduction

This is a wallet app for the [Ledger Nano S](https://www.ledgerwallet.com/products/ledger-nano-s) and [Ledger Blue](https://www.ledgerwallet.com/products/ledger-blue) that makes it possible to store your [CasinoCoin](https://www.casinocoin.org/)-based assets on those devices.

A companion [Javascript library](https://github.com/LedgerHQ/ledgerjs) is available to communicate with this app.


## Building and installing

To build and install the app on your Nano S or Blue you must set up the Ledger Nano S or Blue build environment. Please follow the Getting Started instructions at the [Ledger Nano S github repository](https://github.com/LedgerHQ/ledger-nano-s).

Alternatively, you can set up the Vagrant Virtualbox Ledger environment maintained [here](https://github.com/fix/ledger-vagrant). This sets up an Ubuntu virtual machine with the Ledger build environment already set up. Note that if you are on a Mac, at the time of this writing this seems to be the only way to build and load the app.

Like another alternative you can use [Docker](https://www.docker.com/) for building this project using [this](https://github.com/lotogus/ledger-build-docker) in that project there is an example of how to build this project [here](https://github.com/lotogus/ledger-build-docker#compile-example)


The command to compile and load the app onto the device is:

```$ make load```

To remove the app from the device do:

```$ make delete```
