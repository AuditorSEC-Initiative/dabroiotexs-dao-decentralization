# DAO Constitution — Dabroiotexs Decentralization Initiative

> **Version:** 1.0 · **Status:** Draft · **Network:** IoTeX Mainnet

---

## Preamble

The Dabroiotexs DAO exists to decentralize governance of IoTeX-based infrastructure, ensuring that protocol upgrades, treasury allocations, and partnership decisions are made transparently by token holders rather than any single entity.

---

## Article I — Name & Purpose

**Name:** Dabroiotexs Decentralization DAO (DDD)

**Purpose:**
1. Govern the Dabroiotexs smart-contract suite on IoTeX.
2. Allocate community treasury funds for development, audits, and grants.
3. Ratify protocol upgrades through on-chain voting.
4. Maintain transparency via public governance records.

---

## Article II — Membership

| Tier | Requirement | Rights |
|------|-------------|--------|
| Observer | Holds ≥ 1 DABRX token | View proposals, comment |
| Voter | Holds ≥ 100 DABRX | Submit & vote on proposals |
| Delegate | Elected by ≥ 10,000 DABRX votes | Execute approved proposals |
| Guardian | Multi-sig council (5/9) | Emergency veto (time-locked 48 h) |

---

## Article III — Proposal Lifecycle

```
Draft → Review (72 h) → Voting (7 days) → Timelock (48 h) → Execution
```

### Quorum & Thresholds

| Proposal Type | Quorum | Approval |
|---------------|--------|----------|
| Parameter change | 5% supply | Simple majority |
| Treasury spend > 10k USD | 10% supply | 60% yes |
| Constitutional amendment | 20% supply | 75% yes |
| Emergency action | Guardian council | 5/9 multi-sig |

---

## Article IV — Treasury

- **Address:** `io1…` (published at launch)
- **Funding sources:** Protocol fees (2%), community grants, partner contributions.
- **Spending limits per proposal:** Up to $50,000 USD equivalent without Guardian review; above requires Guardian co-sign.
- **Annual audit:** Required by independent auditor selected via DAO vote.

---

## Article V — Smart-Contract Governance

- All upgradeable contracts use OpenZeppelin `TransparentUpgradeableProxy`.
- Proxy admin is owned by the DAO Timelock contract.
- Critical parameter changes require a 48-hour timelock minimum.
- Emergency pause is available to Guardian multi-sig only, auto-expires in 7 days.

---

## Article VI — Amendments

Amendments to this constitution require:
1. A formal proposal tagged `[CONSTITUTIONAL]`.
2. 20% quorum of circulating supply.
3. 75% supermajority yes vote.
4. 7-day timelock before execution.
5. Publication of amended version with version bump.

---

## Article VII — Dispute Resolution

- On-chain disputes resolved by Guardian multi-sig arbitration.
- Off-chain disputes: community mediation → elected arbitration panel → binding community vote.
- Decisions recorded permanently on IoTeX chain.

---

## Article VIII — Code of Conduct

All participants agree to:
- Act in good faith for the benefit of the protocol.
- Disclose conflicts of interest before voting.
- Refrain from market manipulation or Sybil attacks.
- Respect privacy of other members.

Violations may result in proposal rejection or delegate removal via community vote.

---

## Appendix A — Key Contracts

| Contract | Role | Address |
|----------|------|---------|
| GovernorBravo | Proposal & voting | TBD |
| Timelock | Execution delay | TBD |
| Treasury | Fund custody | TBD |
| DABRX Token | Governance token | TBD |

---

## Appendix B — References

- [IoTeX Developer Docs](https://docs.iotex.io)
- [OpenZeppelin Governor](https://docs.openzeppelin.com/contracts/4.x/governance)
- [Compound Governance](https://compound.finance/governance)
- [MakerDAO Constitution](https://makerdao.world/en/learn/governance)

---

*This constitution is maintained under the [MIT License](../../LICENSE). Community contributions welcome via Pull Request.*
