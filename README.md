# KC

Full-stack engineer. I ship the client, the server, and the glue — from first principles, not from a favorite stack. A lot of that product has been Web3 (payroll, RWA, agent auth). The job is still the system, not the chain.

> **Syntax is cheap. Constraints aren't.** High concurrency is a queueing problem. Low latency is a locality problem. They are usually enemies. I pick the tool the environment needs, not the one I already know.

[site](https://kaushal.is-cool.dev) · [email](mailto:kaushalchaudhari26@gmail.com) · [linkedin](https://www.linkedin.com/in/kaushal-chaudhari-21b83a1b0)

TypeScript · Node · Next.js · PostgreSQL · Redis · Solidity · Rust/Soroban · Stellar · Foundry

---

## Production

**1. [PayZoll](https://github.com/PayZoll-Orgs)** — founding engineer, full stack. B2B cross-border payroll on Stellar (USDC/EUROC): TypeScript/Node + React, PostgreSQL + Redis, GCP. JIT FX, unsigned XDR on the server, Freighter sign in-browser. Keys never leave the client. The team collectively won **[$100k in XLM from Stellar Community Fund #36](https://medium.com/stellar-community/scf-36-round-recap-b35e675dee10)**. [PRs](https://github.com/PayZoll-Orgs/PayZoll-Stellar-Client-v.1/pulls?q=is%3Apr+author%3Akaushalya4s5s7)

**2. [TheOpenAssets](https://github.com/TheOpenAssets/TOA-Client)** — full-stack RWA product. ERC-3643 / T-REX, identity-bound transfers, modular compliance, chain-agnostic execution (Mantle, Creditcoin, Stellar). [Client](https://github.com/TheOpenAssets/TOA-Client) · [Server](https://github.com/TheOpenAssets/TOA-Server) · [X](https://x.com/TheOpenAssets) · [architecture](https://open-assets-core-proposal.notion.site/Open-Assets-Mantle-Network-2d5316cd01a780818164c5889beb1a19) · [pitch](https://www.canva.com/design/DAG2JKBFk-s/0SJRXDvPXhVEFC887f3EbA/view?utm_content=DAG2JKBFk-s&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h488a45ef02&continue_in_browser=true#8)

Credora (RWA line): [OneChain 1st, $3k](https://onehackathon.com/1-0/winners) · U2U $4k · Mantle RWA $2k — only winner on that track that was not already funded.

**3. [AgenticOperations](https://github.com/AgenticOperations)** — full-stack agent ops: on-chain policy / spending firewall. [Casper](https://github.com/AgenticOperations/Casper-AGOPS.Client) ([live](https://aops-casper.up.railway.app)) · [Arc](https://github.com/AgenticOperations/AOPS-PMOA) ([live](https://agentops.up.railway.app)) · [demo](https://x.com/Kaushaly4s5s7/status/2082779793557434477) · [pitch](https://www.canva.com/design/DAHR02R61qU/KYDDwhhX_3aPqNjkhN5Bqg/view?utm_content=DAHR02R61qU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h5be0a20f82&continue_in_browser=true) · [architecture](https://aops.tiiny.site)

**4. [Tesseract Protocol](https://github.com/The-Tesseract-Protocol)** — full-stack confidential settlement on Stellar/Soroban. Decouples business intent from public finality (deposit → wait → withdraw, relayers, distributors, batch rails). [Site](https://tesseractprotocol.xyz) · [architecture](https://tessfi.gitbook.io/docs-tess)

Contributed as [GanuC555](https://github.com/GanuC555) (34 commits on [Tess-Client](https://github.com/The-Tesseract-Protocol/Tess-Client.v.0)): waitlist, token mapping, deposit-notify multi-token, withdraw path, privacy service, bulk batch pay + wallet, auth-tree viz. On [Tess-Server](https://github.com/The-Tesseract-Protocol/Tess-Server.v.0/pull/7): waitlist GET API.

**5. [Noketa](https://noketa.io)** — helping a Czech founder ([Pavel Buchta](https://www.linkedin.com/in/pavelbuchta)) take transactional/omnichannel email **0 → 1**, now scaling **1 → 100**. Shipped SMS, Push, WhatsApp, Instagram + settings end-to-end ([6 PRs](https://github.com/Noketa-io/noketa/pull/12)).

---

## Research

**[MEC-assisted PoW mining](https://github.com/kaushalya4s5s7/MEC-Assisted-PoW-Blockchain-Simulator)** — IIIT Guwahati, under [Dr. Manojit Ghose](https://www.iiitg.ac.in/department/cse/faculty-1/manojit-ghose). Discrete-event sim of offloading Proof-of-Work from mobiles onto an edge computing provider, plus multi-coalition mining. Bloom-filter tx sync: **84.6% bandwidth cut** (689 → 106 KB/s), flat scaling from J=3 to J=7, ~80% latency cut on dual-channel delivery.

---

## Web3

Selected Web3 product and protocol work — still client + server + contracts, not a Solidity-only lane.

- **[Loyalty Lock](https://github.com/kaushalya4s5s7/loyalty-lock-hook)** — Uniswap v4 hook. Time-decaying LP exit fee, donated to remaining LPs. Live on Sepolia.
- **[SlashMarket](https://github.com/kaushalya4s5s7/slashfrontend)** — Tezos L1 + Etherlink L2. PT/YT strip + AI baker selection. [3rd at Now Media × Etherlink/Tezos, $1k](https://x.com/Kaushaly4s5s7/status/2044699627342201130). [Live](https://slashfrontend.vercel.app) · [pitch](https://canva.link/89dei1prszi3rtx)
- **[Bhishi](https://github.com/kaushalya4s5s7/bhishi)** — non-custodial ROSCA on Monad. [Live](https://bhishi.up.railway.app)
- **[Zera](https://github.com/kaushalya4s5s7/Zera_AI)** — generate, test, audit, document a contract. [Open Campus Semester 3](https://x.com/opencampus_xyz/status/1925476891651412133): won 2 tracks, $3k total, invited into the OC Incubator.
- **[ReVault](https://github.com/18Abhinav07/ReVault/pull/1)** — per-issuance dual-tranche (Reg-D / Reg-S), clone factory + NAV oracle. Merged.
- **[KeeperHub #2439](https://github.com/KeeperHub/keeperhub/pull/2439)** — coerce `gasLimitMultiplier` on every execute write route + MCP transfer schema. Merged.
- **[altana-sdk #100](https://github.com/altananetwork/altana-sdk/issues/100)** — MCP session grant/revoke persisted local state when the SDK returned `failed`.

5× hackathon winner · BNB Chain Martian

---

## Also

- **[Envo](https://github.com/kaushalya4s5s7/envo)** — HVAC agent from block-level heat + air quality. [Live](https://envo.up.railway.app)
- **[Plumbline](https://github.com/ByteBell/Plumbline/pull/85)** — one-command install + Ink TUI wizard. Also filed the [plaintext API-key issue](https://github.com/ByteBell/Plumbline/issues/100).

[kaushalchaudhari26@gmail.com](mailto:kaushalchaudhari26@gmail.com)
