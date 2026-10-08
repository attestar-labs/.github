# Attestar Labs

![Built on Stellar](https://img.shields.io/badge/built%20on-Stellar-7D00FF?style=flat-square&logo=stellar&logoColor=white)

**Continuous, private proof of solvency for stablecoin and RWA issuers on Stellar**

An issuer proves on-chain that reserves cover every holder balance — without revealing a single account, custodian, or even the totals.

Built on **Stellar**, the open network for payments and tokenized assets, with logic running on **Soroban** smart contracts.

- *Groth16 in the browser* — proves `on-chain USDC + private off-chain reserves >= liabilities`
- *Real reserve input* — the Soroban contract substitutes the issuer's actual on-chain USDC balance, so the number cannot be faked
- *Selective disclosure* — holders verify their own inclusion; a regulator with a view key reconstructs the full breakdown

Code: https://github.com/attestar-labs/attestar

Stellar: https://stellar.org · Docs: https://developers.stellar.org

*`Soroban` · `Rust` · `Circom` · `Groth16` · `BN254` · `Freighter` · Stellar · Soroban*
