# Guardian Agent

**Understand wallet risks before you sign.**

Guardian Agent is a proposed open-source React integration that turns Webacy risk findings into plain-language explanations inside a dApp's transaction flow. A deterministic policy layer controls the integration's signing gate; AI explains the findings and cannot override that gate.

**Current status: proposal and architecture only.** There is no working SDK, live API integration, published npm package, deployed demo, security audit, or measured performance result yet.

## First release proposed

- Base-first dApp integration, subject to proving the provider's unsigned transaction workflow.
- Risk explanation panel, explicit unavailable states, and configurable branding.
- Transaction and EIP-712 checks, address screening, and read-only approval review, introduced through capability gates.
- Source-linked explanations with a deterministic fallback when AI is unavailable.
- Solana token screening as a separately validated extension; no claim of Solana transaction simulation.

A dApp must explicitly route its signing calls through Guardian. This cannot protect transactions signed outside that integration or guarantee protection from loss.

## Project documents

- [Application answers](docs/APPLICATION.md)
- [Delivery plan](docs/PLAN.md)
- [Architecture](ARCHITECTURE.md)
- [Plan review and primary sources](docs/PLAN_REVIEW.md)
- [Repository setup scope](docs/SETUP_PACKET.md)

## Support requested

API credits and technical onboarding for a bounded integration pilot. The grant listing's headline and detailed funding description differ; see the [review](docs/PLAN_REVIEW.md) before using a cash budget.

## License

[MIT](LICENSE). Webacy services and provider data remain subject to their own terms; this license does not grant redistribution rights to provider responses.
