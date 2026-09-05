# p-money-data

Machine-written round history for [p-money](https://github.com/hera-cross/pmoney-site).

`rounds.json` is committed and pushed by the p-money keeper at the end of every payout round.
Each entry is one round: the snapshot block, the ETH spent, the PONS distributed, the payout
transaction hashes, and the per-wallet amounts. Every figure is verifiable on
[Blockscout](https://robinhoodchain.blockscout.com).

Do not edit by hand — the keeper overwrites this file.
