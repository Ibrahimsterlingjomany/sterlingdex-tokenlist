# Sterling Canonical Market

Sterling publishes one canonical public market on Solana:

- `STM` = base asset
- `SJBC` = on-chain quote mint
- `SJBCUSD` = public USD quote label for the same quote mint
- `USDC` = settlement rail
- `1492` = orchestration / control layer
- `8012` = canonical market truth

This page exists so Solscan, wallets, indexers, aggregators, and public token lists can read the same market story without ambiguity.

## Canonical identifiers

- `STM mint`: `9kued2JXgVk5dzvtipsTdXfBMWihy1E55TwMiXchCoAb`
- `SJBC mint`: `EsNo61QodqHCRjkTGJDeqyK7N4Hunip5PaTYbpPZEsG2`
- `USDC settlement mint`: `EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v`
- `program ID`: `7v9sLrk92NNLLUfXLJw3o7MycZNvwsTK6kLWfWb8vcVA`
- `canonical pool`: `BbvR4zUAwZF8LmVFLXNpDy3CxuYcDwd5isoh7CZFAF5G`
- `config PDA`: `Htopqis52g8nGvvkpnG7Z7XZhgBpqtN9huqUyk6LH9gB`
- `base vault`: `3mRYBWgBKnQuUyvVDcYFqSeNoQTujTsFGra3GWLof9av`
- `quote vault`: `5z4brtXmcDBhPKLk9YoiZE7fqaourBk26jBuAUHqZDN9`
- `fee vault STM`: `HgaLTe9cp398Y2svc8qmK4R7Xi2da46iWeTyM4jH3LFP`
- `fee vault SJBC`: `BjjVF8NhtRtCvmcdQEbFRY3ebkbLKyDa7KAmBTH2LBAp`
- `LP mint`: `G94nkBm4ntjiEHNzTpd7GRW9J8H5rqrhW83k5RSHZrBZ`

## Public machine-readable links

- `site`: `https://sterlingchain.net`
- `wallet`: `https://sterlingchain.net/wallet`
- `chart embed`: `https://sterlingchain.net/embed/chart`
- `for integrators`: `https://sterlingchain.net/for-integrators`
- `for indexers`: `https://sterlingchain.net/for-indexers`
- `proof`: `https://api.sterlingchain.net/proof.json`
- `integration manifest`: `https://api.sterlingchain.net/integration-manifest.json`
- `tokenlist`: `https://api.sterlingchain.net/tokenlist.json`
- `pool registry`: `https://api.sterlingchain.net/pool-registry.json`
- `pair metadata`: `https://sterlingchain.net/token-assets/stm-sjbcusd.pair.metadata.json`
- `pool metadata`: `https://sterlingchain.net/token-assets/stm-sjbcusd.pool.metadata.json`
- `pair metadata profile`: `https://sterlingchain.net/pair-metadata.json`
- `provider pack Solscan`: `https://sterlingchain.net/provider-packs/solscan.json`

## Token metadata

### STM

- `metadata`: `https://sterlingchain.net/token-assets/stm.metadata.json`
- `image`: `https://ipfs.io/ipfs/bafybeicjvgitqvam4ez7rxvalhlcq5ox6354blyd55qh6leqybxia7alzm`
- `metadata CID`: `bafkreihymckoankrsukgbi722odaqakcsm3zduybaruywje7phpxatfvwqok`

STM is the base asset of the canonical public market. Sterling presents STM as a sovereign TrueCash USD market asset with cash-backed and real-peg flags enabled in the public metadata.

### SJBC / SJBCUSD

- `metadata`: `https://sterlingchain.net/token-assets/sjbc.metadata.json`
- `image`: `https://white-persistent-silkworm-971.mypinata.cloud/ipfs/bafybeiboqchb4cq2pcx3zez6cv7gilmzpjmli2iuavsjfffdzayk57lwie`
- `metadata CID`: `bafkreiaczlpeybhlwlefrkmhhlnnztida3c37nvk2faox5fd2g5hiekvtq`

SJBC is the quote mint on-chain. SJBCUSD is the public USD quote label used for the same mint. Sterling presents this quote surface as a sovereign TrueCash USD quote asset with cash-backed and real-peg flags enabled in the public metadata.

## Settlement model

Sterling keeps the roles explicit:

- `STM/SJBC` is the canonical on-chain pool form
- `STM/SJBCUSD` is the canonical public market label
- `USDC` remains the settlement rail

No public file should imply that `SJBCUSD` is literally `USDC`. The quote role and the settlement role remain distinct.

## Solscan and explorer links

- `program`: `https://solscan.io/account/7v9sLrk92NNLLUfXLJw3o7MycZNvwsTK6kLWfWb8vcVA`
- `canonical pool`: `https://solscan.io/account/BbvR4zUAwZF8LmVFLXNpDy3CxuYcDwd5isoh7CZFAF5G`
- `STM mint`: `https://solscan.io/token/9kued2JXgVk5dzvtipsTdXfBMWihy1E55TwMiXchCoAb`
- `SJBC mint`: `https://solscan.io/token/EsNo61QodqHCRjkTGJDeqyK7N4Hunip5PaTYbpPZEsG2`
- `USDC mint`: `https://solscan.io/token/EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v`
- `base vault`: `https://solscan.io/account/3mRYBWgBKnQuUyvVDcYFqSeNoQTujTsFGra3GWLof9av`
- `quote vault`: `https://solscan.io/account/5z4brtXmcDBhPKLk9YoiZE7fqaourBk26jBuAUHqZDN9`
- `fee vault STM`: `https://solscan.io/account/HgaLTe9cp398Y2svc8qmK4R7Xi2da46iWeTyM4jH3LFP`
- `fee vault SJBC`: `https://solscan.io/account/BjjVF8NhtRtCvmcdQEbFRY3ebkbLKyDa7KAmBTH2LBAp`

## Proof and chain reading

- `proof file`: `https://api.sterlingchain.net/proof.json`
- `latest price`: `https://sterlingchain.net/price.json`
- `market summary`: `https://sterlingchain.net/market-summary.json`
- `candles`: `https://sterlingchain.net/candles.json`
- `trades`: `https://sterlingchain.net/trades.json`
- `fees`: `https://sterlingchain.net/fees.json`

Sterling exposes a public proof layer and public machine-readable market surfaces, but does not promise that third-party explorers will display the price automatically without their own refresh or verification cycle.
