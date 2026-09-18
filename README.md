# KC

I like understanding complicated systems and then making them move stupidly fast.

Great engineering is not knowing every tool. It's **knowing what the hell your system is actually doing.** Once I get that, I usually can't stop myself from building on it.

Right now that means three things: **settlement that actually settles**, **compliance that actually enforces**, and **agents that don't get to lie about what they were allowed to do.**

> **Syntax is cheap. Constraints aren't.**
>
> I learned backend from first principles — queues, locks, locality, failure domains — so the language is a detail. High concurrency is a queueing problem. Low latency is a locality problem. They are usually enemies. Mixing them up is how you ship a slow distributed monolith.
>
> I don't pick a tool because I already know it. Every framework was built for a specific use case; using yours because it's mine is how systems fail to scale.
>
> Drop me on a foreign stack. I don't start with the framework. I start with where the bytes wait, where they contend, and what the system is lying about when a write "succeeds." Then I pick the thing this environment actually needs, and I scale from there.

[kaushal.is-cool.dev](https://kaushal.is-cool.dev) · [email](mailto:kaushalchaudhari26@gmail.com) · [linkedin](https://www.linkedin.com/in/kaushal-chaudhari-21b83a1b0) · [x](https://x.com/Kaushaly4s5s7) · [orcid](https://orcid.org/0009-0006-5362-904X)

TypeScript · Solidity · Rust/Soroban · Node · Next.js · PostgreSQL · Redis · Foundry · Stellar/SDP · EVM

~1.9k contributions this year · 70+ repos · 5× hackathon winner · BNB Chain Martian

---

## What I actually ship

**Started with hackathons** — learned Web3 by shipping before I was ready. BNB Chain quarterfinals, EduChain + Tezos EVM wins, Casper AgentOps top demo, and a frankly unhealthy amount of debugging.

**Then the real builds** — PayNova/PayZoll with a friend. All-nighters. Tiny bugs nobody noticed. Somehow it won, then it became a company.

**Then I got obsessed with what happens underneath** — T-REX / ERC-3643 at [TheOpenAssets](https://github.com/TheOpenAssets). Permissions, state, async execution, edge cases. “Compliant” is a lot more fun when you actually have to make it work.

**Then real money entered the chat** — founding engineer at [PayZoll](https://github.com/PayZoll-Orgs). B2B cross-border payroll on Stellar: USDC/EUROC in seconds instead of 3–5 day bank wires. TypeScript/Node + React, PostgreSQL + Redis, GCP. Multi-tenant Stellar Disbursement Platform. Just-in-time FX, unsigned XDR on the server, Freighter sign in-browser. Private keys never leave the client.

**Now I'm playing with agents** — policy / authorization infrastructure for autonomous agents transacting on-chain ([AgenticOperations](https://github.com/AgenticOperations)), plus the session-key / payment-gateway problems sitting next to that.

And yes, I use coding agents aggressively.

**Plan → split → parallelize → ship → repeat.**

The agents can write the code. **I just want to know why the code works.**

---

## Selected work

Work I can talk about in an interview without waving my hands.

- **[Loyalty Lock](https://github.com/kaushalya4s5s7/loyalty-lock-hook)** — Uniswap v4 hook. Time-decaying LP exit fee that donates mercenary churn to the LPs who stay. Live on Sepolia.
- **[Envo](https://github.com/kaushalya4s5s7/envo)** — per-building outdoor brain. Address in; block-level heat + air quality out as HVAC setpoints, shade tint, and damper commands. [Live](https://envo.up.railway.app) · [demo](https://youtu.be/-8r6QPC62YI)
- **[Casper AGOPS](https://github.com/AgenticOperations/Casper-AGOPS.Client)** — multi-agent operations with on-chain policy enforcement and a spending firewall in front of AI agents. Casper buildathon finalist. [Live](https://aops-casper.up.railway.app)
- **[AOPS-PMOA](https://github.com/AgenticOperations/AOPS-PMOA)** — same authorization idea, aimed at the Circle / Arc agentic economy. [Live](https://agentops.up.railway.app)
- **[SlashMarket](https://github.com/kaushalya4s5s7/slashfrontend)** — Tezos L1 + Etherlink L2. Users deposit, strip PT/YT, trade a time-decay AMM; AI agents compete on baker selection with a keccak256 reasoning hash on-chain. [Live](https://slashfrontend.vercel.app)
- **[Bhishi](https://github.com/kaushalya4s5s7/bhishi)** — non-custodial ROSCA on Monad. Rotating savings without an organizer who can vanish with the pot. [Live](https://bhishi.up.railway.app)
- **[Zera](https://github.com/kaushalya4s5s7/Zera_AI)** — generate, test, audit, and document a contract in one pass. EduChain winner.
- **[TOA Client](https://github.com/TheOpenAssets/TOA-Client)** — ERC-3643 / T-REX RWA issuance UI. Identity-bound transfers, not a mint button with a disclaimer.

---

## Open source — merged into other people's trees

Pinned repos show what I built. This is what other maintainers accepted.

- **[KeeperHub #2439](https://github.com/KeeperHub/keeperhub/pull/2439)** — `gasLimitMultiplier` was only honored on some execute write paths. Coerced it on transfer, contract-call, check-and-execute, and the MCP transfer schema so a canvas `maxGasLimit` object couldn't silently miss the chain. Merged.
- **[Noketa](https://github.com/Noketa-io/noketa)** — six merged PRs that took an email kitchen to omnichannel: SMS, Push, WhatsApp, Instagram, plus channel settings wired end-to-end ([#6](https://github.com/Noketa-io/noketa/pull/6), [#8](https://github.com/Noketa-io/noketa/pull/8), [#9](https://github.com/Noketa-io/noketa/pull/9), [#11](https://github.com/Noketa-io/noketa/pull/11), [#12](https://github.com/Noketa-io/noketa/pull/12)).
- **[ByteBell / Plumbline #85](https://github.com/ByteBell/Plumbline/pull/85)** — `curl | bash` install plus a 4-stage Ink TUI setup wizard (provider, credentials, optional repo, confirm). ~2k lines. Merged.
- **[ReVault #1](https://github.com/18Abhinav07/ReVault/pull/1)** — replaced a singleton Reg-D / Reg-S pool with per-issuance dual-tranche tokens, EIP-1167 clone factory, and a NAV oracle. Merged.
- **[TheOpenAssets / TOA-Client](https://github.com/TheOpenAssets/TOA-Client)** — 404s, marketplace buy path, borrow merge. Merged.
- **[PayZoll Stellar client](https://github.com/PayZoll-Orgs/PayZoll-Stellar-Client-v.1)** — onboarding UI, API handling, error surfaces, restricted-mode copy, type fixes. Private org, public receipt is the PR history.

---

## Issues I opened because the happy path was lying

I raise issues when the code already *thinks* it succeeded.

- **[altana-sdk #100](https://github.com/altananetwork/altana-sdk/issues/100)** — MCP `grant_session` / `revoke_session` persist local keychain state even when the SDK returns `status: "failed"`. Local truth diverges from chain truth.
- **[ByteBell / Plumbline #100](https://github.com/ByteBell/Plumbline/issues/100)** — `openrouter_api_key` stored as plaintext in `~/.bytebell/config.json`. The schema hints at `bytebell keys set` / keychain. That command does not exist.
- **[AgenticOperations / Documents #1](https://github.com/AgenticOperations/Documents/issues/1)** — treat authorization *decision data* as a product moat, not a log line. If an agent got a yes or a no, you should be able to prove why later.
- **[ByteBell / Plumbline #84](https://github.com/ByteBell/Plumbline/issues/84)** — first-run install was a wiki page. Filed the feature, then shipped the wizard in #85.

---

## How I work

If a write path has three doors, I check all three. If a status enum has `"failed"`, I don't write the keychain anyway. If the README documents a secrets command that isn't in the binary, that's a bug, not a backlog item.

If you're building something hard, I'm probably already interested.

**kaushalchaudhari26@gmail.com**
