# Cardano Enterprise Adoption: Production Ticketing Platform — Treasury Withdrawal

This repository hosts the on-chain **governance-action metadata** and the **full proposal** for a Cardano **Treasury Withdrawal** by **Anvil Development Agency** and **Sellout**.

It funds **Phase 2** of a production, Cardano-native ticketing platform — a secondary marketplace with on-chain royalty enforcement, per-event anti-scalping controls, custodial wallet onboarding for Sellout's 200,000+ existing users, organizer tools, an independent third-party security audit, and a public launch campaign — anchored by the contracted Yellowstone Club 2026 concert series.

## At a glance

| | |
|---|---|
| Governance action type | Treasury Withdrawal |
| Requested amount | ₳4,969,231 (~$1,093,231 USD at $0.22/ADA) |
| Duration | 8 months |
| Administrator | Intersect (budget administrator, by prior agreement) |
| Author | Anvil Development Agency, Inc. (ada-anvil.io) + Sellout (sellout.io) |

## Files

- **[`sellout-treasury-withdrawal.metadata.jsonld`](./sellout-treasury-withdrawal.metadata.jsonld)** — the CIP-100 / CIP-108 governance-action metadata (the on-chain anchor target).
- **[`sellout-treasury-withdrawal.proposal.html`](./sellout-treasury-withdrawal.proposal.html)** — the full proposal, formatted for reading.
- **[`sellout-treasury-withdrawal.proposal.md`](./sellout-treasury-withdrawal.proposal.md)** — the full proposal in Markdown.

The complete proposal text (abstract, motivation, rationale, capital allocation, milestones, team, budget administration, and Article IV constitutionality disclosures) is embedded directly in the metadata's `rationale` field, so governance tools render it from the anchor.

## Verifying the metadata

The on-chain action references this metadata by **URL + blake2b-256 hash**. To verify the hash of the metadata file:

```bash
b2sum -l 256 sellout-treasury-withdrawal.metadata.jsonld
```

## Links

- Interactive proposal website: https://fixticketing.com
- Anvil Development Agency: https://ada-anvil.io
- Sellout: https://sellout.io

Contact: pb@ada-anvil.io
