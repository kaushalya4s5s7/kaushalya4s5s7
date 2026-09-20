# KC

Blockchain engineer. I build settlement, compliance, and authorization systems on-chain — from first principles, not from a favorite stack.

> **Syntax is cheap. Constraints aren't.** High concurrency is a queueing problem. Low latency is a locality problem. They are usually enemies. I pick the tool the environment needs, not the one I already know.

[site](https://kaushal.is-cool.dev) · [email](mailto:kaushalchaudhari26@gmail.com) · [linkedin](https://www.linkedin.com/in/kaushal-chaudhari-21b83a1b0)

Solidity · Rust/Soroban · TypeScript · Stellar/SDP · EVM · Foundry · PostgreSQL · Redis

---

## Production

**1. [PayZoll](https://github.com/PayZoll-Orgs)** — founding engineer. B2B cross-border payroll on Stellar (USDC/EUROC). JIT FX, unsigned XDR on the server, Freighter sign in-browser. Keys never leave the client. [PRs](https://github.com/PayZoll-Orgs/PayZoll-Stellar-Client-v.1/pulls?q=is%3Apr+author%3Akaushalya4s5s7)

**2. [TheOpenAssets](https://github.com/TheOpenAssets/TOA-Client)** — ERC-3643 / T-REX. Identity-bound transfers, modular compliance, chain-agnostic RWA execution (Mantle, Creditcoin, Stellar). [Client](https://github.com/TheOpenAssets/TOA-Client) · [Server](https://github.com/TheOpenAssets/TOA-Server)

**3. [AgenticOperations](https://github.com/AgenticOperations)** — on-chain policy / spending firewall for autonomous agents. [Casper](https://github.com/AgenticOperations/Casper-AGOPS.Client) ([live](https://aops-casper.up.railway.app)) · [Arc](https://github.com/AgenticOperations/AOPS-PMOA) ([live](https://agentops.up.railway.app))

**4. [Tesseract Protocol](https://github.com/The-Tesseract-Protocol)** — confidential institutional settlement on Stellar/Soroban. Decouples business intent from public finality (deposit → wait → withdraw, relayers, distributors, batch rails). [Site](https://tesseractprotocol.xyz)

Contributed as [GanuC555](https://github.com/GanuC555) (34 commits on [Tess-Client](https://github.com/The-Tesseract-Protocol/Tess-Client.v.0)): waitlist, token mapping, deposit-notify multi-token, withdraw path, privacy service, bulk batch pay + wallet, auth-tree viz. On [Tess-Server](https://github.com/The-Tesseract-Protocol/Tess-Server.v.0/pull/7): waitlist GET API.

---

## Research

**[MEC-assisted PoW mining](https://github.com/kaushalya4s5s7/MEC-Assisted-PoW-Blockchain-Simulator)** — IIIT Guwahati. Discrete-event sim of offloading Proof-of-Work from mobiles onto an edge computing provider, plus multi-coalition mining. Bloom-filter tx sync: **84.6% bandwidth cut** (689 → 106 KB/s), flat scaling from J=3 to J=7, ~80% latency cut on dual-channel delivery.

---

## On-chain work

- **[Loyalty Lock](https://github.com/kaushalya4s5s7/loyalty-lock-hook)** — Uniswap v4 hook. Time-decaying LP exit fee, donated to remaining LPs. Live on Sepolia.
- **[SlashMarket](https://github.com/kaushalya4s5s7/slashfrontend)** — Tezos L1 + Etherlink L2. PT/YT strip + AI baker selection. [Live](https://slashfrontend.vercel.app)
- **[Bhishi](https://github.com/kaushalya4s5s7/bhishi)** — non-custodial ROSCA on Monad. [Live](https://bhishi.up.railway.app)
- **[Zera](https://github.com/kaushalya4s5s7/Zera_AI)** — generate, test, audit, document a contract. EduChain winner.
- **[ReVault](https://github.com/18Abhinav07/ReVault/pull/1)** — per-issuance dual-tranche (Reg-D / Reg-S), clone factory + NAV oracle. Merged.
- **[KeeperHub #2439](https://github.com/KeeperHub/keeperhub/pull/2439)** — coerce `gasLimitMultiplier` on every execute write route + MCP transfer schema. Merged.
- **[altana-sdk #100](https://github.com/altananetwork/altana-sdk/issues/100)** — MCP session grant/revoke persisted local state when the SDK returned `failed`.

5× hackathon winner · BNB Chain Martian

---

## Other

Not the main story. Still shipped.

- **[Envo](https://github.com/kaushalya4s5s7/envo)** — HVAC agent from block-level heat + air quality. [Live](https://envo.up.railway.app)
- **[Noketa](https://github.com/Noketa-io/noketa/pull/12)** — omnichannel messaging (SMS, Push, WhatsApp, Instagram). 6 PRs merged.
- **[Plumbline](https://github.com/ByteBell/Plumbline/pull/85)** — one-command install + Ink TUI wizard. Also filed the [plaintext API-key issue](https://github.com/ByteBell/Plumbline/issues/100).

[kaushalchaudhari26@gmail.com](mailto:kaushalchaudhari26@gmail.com)
