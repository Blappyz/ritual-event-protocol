# Ritual Event Protocol (REP)

**A non-monetary coordination grammar for small-scale communities.**

REP is a minimal protocol for recording bilateral commitments between community members — what one person offers, what the other requests — witnessed by at least two people, with a built-in expiry date.

It is not a currency. Not a ledger. Not a platform. It is a witnessing layer.

---

## What REP Is

- A physical card format and digital record structure for community exchanges
- Designed for communities of 15–150 people operating without monetary infrastructure
- Built to sit alongside existing reciprocal labor traditions (Parma, Ilima, Minga, Meitheal, and equivalents worldwide)
- Forkable by any community without permission from anyone

## What REP Is Not

- REP has no unit of account and no stored value
- REP cannot enforce anything — enforcement is social, not technical
- REP cannot scale — it replicates by forking
- REP has no owner — it cannot be licensed, sold, or platformed

---

## Repository Contents

```
/
├── README.md                          ← This file
├── RFC-001_Specification.md           ← Full protocol specification
├── card/
│   └── REP_card_reference.png         ← Physical card reference design
├── templates/
│   ├── REP_Nepal_Pilot_Template.xlsx  ← Nepal pilot CSV template
│   └── REP_Namibia_Pilot_Template.xlsx← Namibia pilot CSV template
└── NOOWNER.md                         ← Statement on why REP carries no license
```

---

## The Core Record

Every REP record contains:

| Field | Description |
|-------|-------------|
| Record ID | `[PREFIX]-[YEAR]-[NNN]` e.g. `NPL-2024-017` |
| Created Date | Date both parties agreed |
| Expires Date | Typically 7 days after creation |
| Participant A | Full name — the party making the Offer |
| Participant B | Full name — the party making the Request |
| Offer | Plain language description. No prices. |
| Request | Plain language description. No prices. |
| Witness 1 | Full name. Physically present. |
| Witness 2 | Full name. Physically present. Minimum 2 required. |
| Status | Active / Completed / Unresolved / Abandoned |

---

## How to Fork This

1. Copy this repository
2. Choose a new ID prefix for your community (e.g. `KAV-`, `MNG-`, `MTH-`)
3. Adapt the card watermark to a locally meaningful motif
4. Translate the card fields into your community's language
5. Print cards and start witnessing

No permission required. No notification required. No registration anywhere.

---

## Pilot Communities

REP is currently being introduced in two pilot contexts:

- **Nepal — Gandaki Province**: Communities with existing Parma rotational labor exchange traditions
- **Namibia — Kavango and Zambezi Regions**: Communities with existing Ilima communal work party traditions

---

## The Introduction

The framing for a village elder is simple:

> *"You already do this. This card just remembers it."*

---

## No Owner

This repository has no owner. The protocol has no owner. Fork it, translate it, adapt it, print it, use it. The only thing REP asks is that you do not claim to own it either.

See `NOOWNER.md` for the full statement.

---

## Contact

This protocol was developed in open collaboration. If you are a researcher, community practitioner, or translator working with relevant communities and want to connect, open an issue in this repository.
