---
layout: app

permalink: /zelcore/
description: ZelCore Wallet

icons:
  - zelcore/icons/256x256/zelcore.png

screenshots:
  - zelcore/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: ZelCore
    Comment: ZelCore Wallet
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: zelcore
    X-AppImage-Version: 1.1.0
    X-AppImage-BuildId: 1c7491e0-bdd7-11a8-31e5-f176312a0249
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  private: true
  release: Public release
  repository:
    type: git
    url: git://github.com/zelcash/ZelTreZ.git
  description: ZelCore Wallet
  license: UNLICENSED
  main: "./dist/electron/main.js"
  dependencies:
    abi: file:lib/abi
    axios: "^0.16.1"
    bchaddrjs: "^0.2.2"
    bip32-utils: git://github.com/TheTrunk/bip32-utils.git#master
    bitcoin: "^3.0.1"
    bitcoinjs-lib: git://github.com/TheTrunk/bitcoinjs-lib.git#master
    bitgo-utxo-lib: "^1.0.0"
    bs58check: "^2.0.2"
    changelly: file:lib/changelly
    clipboardy: git+https://github.com/klayveR/clipboardy.git
    chart.js: "^2.7.2"
    copy-to-clipboard: "^3.0.8"
    d3: "^5.7.0"
    electron-log: "^2.2.17"
    element-ui: "^2.1.0"
    ethereumjs-tx: "^1.3.4"
    filepath: "^1.1.0"
    fullnode: file:lib/fullnode
    jayson: "^2.0.1"
    js-sha3: "^0.7.0"
    node-cmd: "^3.0.0"
    omni-simple-send: "^0.0.1"
    qrcode.vue: "^1.6.0"
    qs: "^6.5.2"
    request: "^2.83.0"
    request-progress: "^3.0.0"
    secp256k1: "^3.5.0"
    socket.io-client: "^1.4.6"
    store: "^2.0.12"
    utils: file:lib/utils
    v-tooltip: "^2.0.0-rc.32"
    vue: "^2.3.3"
    vue-awesome: "^2.3.5"
    vue-chartjs: "^3.3.1"
    vue-electron: "^1.0.6"
    vue-router: "^2.5.3"
    vue2-filters: "^0.3.0"
    vuex: "^3.0.1"
    web3: 1.0.0-beta.35
    zelcashrpc: file:lib/zelcashrpc
    zeltrezjs: git://github.com/TheTrunk/zeltrezjs.git#master
---