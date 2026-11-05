# security-research

Smart contract security research — bug bounty write-ups, PoCs, and tooling.

## Focus

DeFi security research across AMM, lending, vaults, governance, and bridges — with local-fork proof-of-concepts before anything is reported.

## Methodology

1. **Enumerate** — map the scope, contracts, and trust boundaries.
2. **Static analysis** — Slither, Aderyn, and manual review.
3. **Fork PoC** — reproduce on a local mainnet fork (Foundry) before calling anything a finding.
4. **Triage** — severity by impact, checked against known-issue databases.
5. **Report** — responsible disclosure through the program official channel. Findings are published here only after submission, fix, and disclosure clearance.

## Tooling

- Foundry (forge / cast) — fork testing and PoCs
- Slither, Aderyn — static analysis
- Echidna, Medusa, Halmos, Mythril — fuzzing and symbolic execution
- Immunefi, Cantina, CodeHawks, Sherlock — bounty platforms

## Write-ups

Published findings and audit notes live under `writeups/`. Nothing here is a live, unpatched vulnerability — findings are published only after they have been submitted, fixed, and cleared for disclosure.

## Disclosure

If you find a vulnerability in this repository tooling, please open an issue or reach out privately. Do not use this repository to disclose live vulnerabilities in third-party protocols.
