## OffCKB

ckb development environment for professionals

## Install

```sh
git clone https://github.com/RetricSu/offckb.git
cd offckb && alias offckb='yarn start'
```

eventually you will do simple
```sh
npm install -g offckb // not yet, todo
```

## Usage

```sh
offckb node // start the devnet of CKB 
offckb init // init a typescript boilerplate with lumos to get started with to build CKB DAPP,think 'hardhat init'
offckb list-hashes // list scripts hashes, equals `ckb list-hashes`
offckb list-accounts // todo, list accounts with prefund CKB tokens
```

### Built-in scripts

- [x] xUDT https://github.com/nervosnetwork/rfcs/pull/428
- [x] Omnilock https://github.com/cryptape/omnilock
- [x] AnyoneCanPay https://github.com/cryptape/anyone-can-pay
- [x] AlwaysSuccess https://github.com/nervosnetwork/ckb-production-scripts/blob/master/c/always_success.c
- [ ] Spore https://github.com/sporeprotocol/spore-contract

### Accounts
```
6109170b275a09ad54877b82f7d9930f88cab5717d484fb4741ae9d1dd078cd6
9f315d5a9618a39fdc487c7a67a8581d40b045bd7a42d83648ca80ef3b2cb4a1
59ddda57ba06d6e9c5fa9040bdb98b4b098c2fce6520d39f51bc5e825364697a
f4a1fc19468b51ba9d1f0f5441fa3f4d91e625b2af105e1e37cc54bf9b19c0a1
0334ddff3b1e19af5c5fddda8dbcfb235416eaaba11cfca8acf63ad46e9f55b2
6f358d92f408511707803d292efa148236a2e114d73a472be2a07e0ba49200c7
bde2f19c98dc5ab4cc98f73c573757a9f1782dc44398022a23f77ca752ad8fbe
7c1280118923ea96529909638dac9bd258251a222783f91dedbf82de15526fd2
1fe1356d47224f34788eb099c4f67ab28a477a5a85d6ff4e54c240c11a0c693c
c3255dd2bbc3accc69c82bdb2c927ab4a681146331d5e01990890fb3cd732b47
8c3f8a6a6847a31af93000a31629f0c674e0cbb1b7cb71bdfbf4fb9dd828a518
11e34fc1bad213b1ce3071501a18c39e5dbf1ea2e66ac05059c36a5d1e7a56cf
0a0ecce6f15c444e6d0013d6eb79c87babff2c76447f3a2f6b28023490170c1f
006250e940dbce94ad9329ac16c109acf7de98c7e4738013bdd3105d4f004d8a
fc8142dc0a6c1dc9102696e7ca730b8c05e233549ea924fafa477f5086d94ac3
711aa98da3e9643170de94d6b16d3a30edf4bb231aa793aaac0fc7373c0f6322
76f51bf03e38b7f4a3c2cd8b088103e746f0e425fb0c5e0f8b22061f41c790cc
1ef1c9cbf031d7bc181c039cebb4f2914dbad689ab268e192fe22ea314d9b4a4
a5808e79c243d8e026a034273ad7a5ccdcb2f982392fd0230442b1734c98a4c2
ace08599f3174f4376ae51fdc30950d4f2d731440382bb0aa1b6b0bd3a9728cd
```

## Development

update built-in scripts:

update submodule inside `docker` and then run
```sh
make all
```
