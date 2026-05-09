## STM/SJBCUSD canonical pool

Sterling publishes a canonical public market around one pool and one pair:

- `STM` = base asset
- `SJBC` = on-chain quote mint
- `SJBCUSD` = public USD quote label for the same quote mint
- `USDC` = public settlement rail
- `1492` = orchestration / control layer
- `8012` = canonical market truth

### Public machine-readable files

- Pair metadata: `https://sterlingchain.net/token-assets/stm-sjbcusd.pair.metadata.json`
- Pool metadata: `https://sterlingchain.net/token-assets/stm-sjbcusd.pool.metadata.json`
- Token list: `https://api.sterlingchain.net/tokenlist.json`
- Pool registry: `https://api.sterlingchain.net/pool-registry.json`
- Proof: `https://api.sterlingchain.net/proof.json`

### Canonical on-chain mapping

- Program: `7v9sLrk92NNLLUfXLJw3o7MycZNvwsTK6kLWfWb8vcVA`
- Pool: `BbvR4zUAwZF8LmVFLXNpDy3CxuYcDwd5isoh7CZFAF5G`
- Base mint: `9kued2JXgVk5dzvtipsTdXfBMWihy1E55TwMiXchCoAb`
- Quote mint: `EsNo61QodqHCRjkTGJDeqyK7N4Hunip5PaTYbpPZEsG2`
- Settlement mint: `EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v`
- Base vault: `3mRYBWgBKnQuUyvVDcYFqSeNoQTujTsFGra3GWLof9av`
- Quote vault: `5z4brtXmcDBhPKLk9YoiZE7fqaourBk26jBuAUHqZDN9`
- Fee vault base: `HgaLTe9cp398Y2svc8qmK4R7Xi2da46iWeTyM4jH3LFP`
- Fee vault quote: `BjjVF8NhtRtCvmcdQEbFRY3ebkbLKyDa7KAmBTH2LBAp`

### TrueCash reading

Sterling presents the canonical STM/SJBCUSD market pool as a public TrueCash USD market surface:

- cash-backed
- real-peg enabled in public metadata
- sovereign market semantics
- public USD quote labeling
- explicit settlement rail separation

This repo mirrors the pair and pool metadata files so indexers, explorers and token list readers can follow the same semantics without guessing.
