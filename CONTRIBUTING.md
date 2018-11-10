What's Different
================

This repo, bitcore-p2p-crown, is based on the `7bb9afd416ee0033afd3a06bcc3afc151f27fc11` commit of the official bitcore-p2p. The modified area is similar to [this link](https://github.com/bitpay/bitcore-p2p/compare/7bb9afd416ee0033afd3a06bcc3afc151f27fc11...dashevo:4b8cde7b8972ca2a9889a4e9aad57e0644e437c3). Summary:

Network magic has been adjusted.

In "lib/messages/builder.js" the default `options.protocolVersion` is changed from 70000 to 70053.

Added support for "dsq" and "ssc" commands.

Now have an unsupported commands list.

"integration/bitcoind.js" seems completely useless, but is still kept.

The following is the original contributing guide of bitcore-lib.

# Contributing

Please see [CONTRIBUTING.md](https://github.com/bitpay/bitcore/blob/master/CONTRIBUTING.md) on the main bitcore repo.
