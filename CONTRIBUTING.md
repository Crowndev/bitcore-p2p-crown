What's Different
================

This repo, bitcore-p2p-crown, is based on the `7bb9afd416ee0033afd3a06bcc3afc151f27fc11` commit of the official bitcore-p2p. The modified area is similar to [this link](https://github.com/bitpay/bitcore-p2p/compare/7bb9afd416ee0033afd3a06bcc3afc151f27fc11...dashevo:4b8cde7b8972ca2a9889a4e9aad57e0644e437c3).

Network magic has been adjusted.

"integration/bitcoind.js" seems completely useless, but is still kept.

In the Dash fork, a line is added to `_buildFromBuffer` function in "lib/messages/index.js":

```js
if (command === 'sendheaders') return; // BIP 130, ignore 'sendheaders' command
```

But I don't know whether it's necessary so I didn't add this line.

The following is the original contributing guide of bitcore-lib.

# Contributing

Please see [CONTRIBUTING.md](https://github.com/bitpay/bitcore/blob/master/CONTRIBUTING.md) on the main bitcore repo.
