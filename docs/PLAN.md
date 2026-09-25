# Delivery plan

All implementation milestones are proposed and unstarted. Time estimates are planning targets, not grant commitments or acceptance records. Advance only when the required dependency is proven.

## Milestones

| Gate | Target effort | Deliverable | Exit demonstration |
| --- | --- | --- | --- |
| 1: Provider capability | Week 1 | Account access, endpoint mappings, Base unsigned transaction and typed-data feasibility | Actual permitted responses; documented chain/endpoint coverage; unsigned input demonstrated without issuing a signature |
| 2: Deterministic core | Week 2 | Server adapter and policy implementation | Same inputs and policy yield same outcome; failures never reach signing |
| 3: User flow | Week 3 | React UI and one reference integration | Action mutation, account/chain changes, cancellation, warnings, and unavailable results exercised end-to-end |
| 4: Pilot package | Week 4 | Demo, instructions, evaluation report, developer feedback | Reproducible setup; measured latency and explanation grounding; actual limitations published |

If Gate 1 fails, stop pre-signing implementation and agree a read-only screening deliverable. Do not silently substitute a transaction-hash lookup for a pre-signing simulation. Each future execution packet must establish its own scope and dependency proofs.

## Planned checks

- Policy: no-risk-findings, warning, block, unavailable, malformed payload, unknown field, unsupported chain, rate limit, timeout, stale result, and conflicting findings.
- Wallet flow: changed payload, changed account/chain, concurrent requests, scan reuse, user rejection, duplicate clicks, and unsupported signing methods.
- AI: at least 30 curated scenarios with permitted fixtures; no unsupported factual claims on that set; compare fixed and AI explanations; report limitations rather than extrapolate a safety rate.
- Security: hostile metadata and prompt injection, secret leakage, unauthorized proxy use, malicious URL input, and dependency review.
- Performance: report sample count, p50/p95, provider latency, policy latency, explanation latency, and cache state separately. Set a performance target after measurement.
- Pilot: seek one developer integration and five comprehension sessions; these are recruitment targets, not existing traction.

Use synthetic fixtures clearly labelled as such. Provider recordings require access and redistribution permission; redact identifying data. Testnet support must be verified per endpoint. Use mocks and read-only calls where necessary; do not spend funds to prove the integration.

## Deferred

Solana transaction interception, Jupiter/Uniswap production swaps, bulk revocation, browser extension, Telegram app, billing, broad multi-chain support, regional threat detection, and invite-only holder analysis. Solana token screening may be added after a separate capability check.

## Resources

API credits are the proposed grant request. Hosting, LLM usage, developer time, and an independent security review need a separate resourcing decision. No third-party audit is purchased or guaranteed. Require an appropriately scoped independent review before a production signing rollout.

## Dependencies for later implementation

| Dependency | Classification | Resolution |
| --- | --- | --- |
| Webacy credential and endpoint entitlement | MISSING | Obtain through the provider without committing credentials |
| Actual unsigned request and response compatibility | UNCLEAR | Resolve guide/reference mismatch with provider and live calls |
| Grant instrument and credit terms | UNCLEAR | Confirm with funder |
| Non-credit operating resources and builder availability | UNCLEAR | Applicant confirms |
| Pilot participant | MISSING | Recruit after a demonstrable reference flow |
| Provider fixture redistribution rights | UNCLEAR | Verify terms before publishing provider data |
| Solana transaction simulation | MISSING | Excluded from first release |

These are implementation blockers, not prerequisites for publishing a clearly labelled proposal.
