<div align="center">

## Attestar Labs

Continuous, private proof of solvency for stablecoin and RWA issuers on Stellar

[![repo](https://img.shields.io/badge/github-attestar-84cc16?style=flat-square&logo=github)](https://github.com/attestar-labs/attestar)

</div>

An issuer proves on-chain that reserves cover every holder balance — without revealing a single account, custodian, or even the totals.

### Inside the repo

- **Groth16 in the browser** — proves `on-chain USDC + private off-chain reserves >= liabilities`
- **Real reserve input** — the Soroban contract substitutes the issuer's actual on-chain USDC balance, so the number cannot be faked
- **Selective disclosure** — holders verify their own inclusion; a regulator with a view key reconstructs the full breakdown

### Links

- Source: https://github.com/attestar-labs/attestar
- Stack: `Soroban` · `Rust` · `Circom` · `Groth16` · `BN254` · `Freighter`
