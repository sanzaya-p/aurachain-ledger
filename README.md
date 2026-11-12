# AuraChain Quantum (`aurachain-quantum-1`) — Live Cryptographic Block & State Ledger

This repository is the public, append-only **Git-Tree Compare-And-Swap (CAS) Ledger Archive** for **AuraChain Quantum v1.1** (`aurachain-quantum-1`).

- **Live Super-App & Browser Miner:** https://aurachain-quantum.vercel.app
- **Live Adoption & Activity Feed:** https://aurachain-quantum.vercel.app/activity
- **Protocol Source Code & CLI:** https://github.com/sanzaya-p/aurachain

## Structure
- `head.json` — Canonical chain tip, active validator weights, BFT finality checkpoint, `.aura` Quantum identity registry, Town Square wall, DEX pools, NFTs, and DAO state.
- `b/<height>.json` — Immutable individual blocks from Genesis `#0` onward, each signed with **Hybrid Ed25519 + NIST FIPS 204 ML-DSA-44** and committed via **SHA3-256** Merkle & state roots.