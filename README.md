[![MFKDF](./logo-sm.png "MFKDF WALLET")](https://wallet.mfkdf.com/ "MFKDF WALLET")

MFKDF Wallet Demo

[![GitHub issues](https://img.shields.io/github/issues/multifactor/mfkdf-wallet-demo)](https://github.com/multifactor/mfkdf-wallet-demo/issues)
[![MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/multifactor/mfkdf-wallet-demo/blob/master/LICENSE)

[View Demo](https://wallet.mfkdf.com) |
[Demo Video](https://www.youtube.com/watch?v=cB44BMGnFIs) |
[MFKDF Repo](https://github.com/multifactor/mfkdf) |
[MFKDF Site](https://mfkdf.com/) |
[MFKDF Docs](https://mfkdf.com/docs/) |
[Multifactor](https://github.com/multifactor) |
[Author](https://github.com/VCNinc)

This repository illustrates how to use MFKDF to build a strong trustless decentralized cryptocurrency wallet application featuring multi-factor key derivation with self-service key recovery. It uses IPFS and IPNS to store MFKDF policy files. The application exists for demonstration purposes only. It has not been tested/audited as thoroughly as the core MFKDF library, and is not intended to be used as a production-ready application.

Based on the 2017 [eth-hot-wallet](https://github.com/PaulLaux/eth-hot-wallet) project by [Paul Laux](https://github.com/PaulLaux).

Copyright ©2022 Vivek Nair, ©2017 Paul Laux • [MIT](https://github.com/multifactor/mfkdf-wallet-demo/blob/master/LICENSE)

## 运行

1. `pn i`
2. `pn start:tunnel`

## 坑

1. 某些服务端接口是不通的，像发邮件之类的接口，需要手动输出看看结果，然后将地址放到浏览器地址栏中
