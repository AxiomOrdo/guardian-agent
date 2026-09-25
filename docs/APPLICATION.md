# Guardian Agent — application draft

Use the answers matching the actual form fields. This is a proposal, not a claim that the integration already exists. Personal history, availability, and portfolio links must be supplied by the applicant.

## Project name

Guardian Agent

## Tagline

Plain-language wallet risk checks, embedded before signing.

## Short description

Guardian Agent is a proposed open-source React SDK and reference dApp that will translate Webacy risk findings into clear explanations before users sign. We will start with a bounded Base integration, combining provider-backed checks with deterministic signing rules and an explicit unavailable state. AI will explain findings without inventing scores or overriding policy. The goal is a reusable, configurable interface that helps dApp developers present risks where users make decisions.

## Problem and solution

Wallet risk data is only useful when users can understand it at the point of action. Guardian Agent will connect provider findings to a concise explanation of the proposed action, the detected risks, and the limits of the scan. Developers will integrate a React component and an explicit signing wrapper, with keys held on the server. Unknown or incomplete results will stop the protected flow instead of producing a reassuring label.

## Webacy integration

We propose Base as the first chain. Our initial technical milestone is to validate access, response formats, and support for scanning unsigned transaction requests. We will then integrate transaction and EIP-712 analysis, address screening, and read-only approval review as each capability is proven. URL checks and Solana token screening are later extensions. We will not claim Solana transaction simulation or access to invite-only holder analysis without verification.

## Differentiation

Guardian Agent will focus on a tested signing workflow and explanations tied to the specific provider findings. Its intended contribution is reusable integration code, visible coverage limits, and failure handling that developers can inspect. AI is an explanation layer; deterministic policy controls the signing gate. We will measure comprehension, integration effort, latency, and failure behavior rather than claim unique detection intelligence or guaranteed safety.

## Delivery plan

Target: four weeks after API access and technical prerequisites are confirmed, with contingency for provider integration issues.

1. Validate endpoint access and unsigned request support; document response mappings and limitations.
2. Build the server adapter and deterministic policy behavior; test unavailable, malformed, stale, and unsupported responses.
3. Build the React panel and one Base reference flow; add grounded explanations and deterministic fallback text.
4. Publish a reproducible demo, installation guide, evaluation results, and measured latency. Seek feedback from a small developer pilot.

If pre-signing support cannot be proven, the initial deliverable will be explicitly limited to read-only screening. We will agree any milestone change with the grant team rather than describe that fallback as transaction protection.

## Funding and support requested

We request up to $10,000 in DD.xyz API credits, sized with the Webacy team against the pilot's expected usage, plus technical onboarding. Credits would support endpoint qualification, regression scenarios, integration testing, and a bounded developer pilot. Please confirm the award instrument, eligible endpoints, quotas, credit expiry, and any additional support available. We have not assumed that credits can fund founder compensation, hosting, an LLM, or an external security review.

## Current progress

We have published the project proposal, architecture, delivery milestones, and a source-backed review at https://github.com/AxiomOrdo/guardian-agent. Implementation and live API validation have not started. No demo or performance claim is being made at application stage.

## Intended users and adoption

Initial users are developers building Base dApps who need a reusable risk explanation and signing workflow. We will seek one design partner and test whether users understand the warnings before expanding. English is the first language; Thai localization and Solana token screening are follow-on work subject to user feedback and verified coverage. No partnerships or user numbers are claimed.

## Team and skills — complete personally

Project submitted under AxiomOrdo. Add your name, actual role, relevant public project links, verified technical experience, and realistic weekly availability. List only skills you can substantiate. Do not copy the original claims of ten years' experience, Rust/Anchor mastery, full-time availability, or a 3–5x productivity multiplier unless independently true.

## Links

Repository: https://github.com/AxiomOrdo/guardian-agent

Demo: not available yet.

Application: https://superteam.fun/earn/grants/startup-accelerator-grant
