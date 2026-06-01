<div align="center">

<img src="https://raw.githubusercontent.com/greencalculus/.github/main/profile/assets/greencalculus-logo.png" width="72" height="72" alt="GreenCalculus" />

# Jeremiah Say

### Lead Systems Architect — Carbon Accounting & Environmental Calculation Engines

**I build carbon math you can audit.**

[greencalculus.com](https://greencalculus.com) · [GitHub org](https://github.com/greencalculus) · [About](https://greencalculus.com/about/jeremiah-say/) · [LinkedIn](https://www.linkedin.com/in/jeremiahsay/)

![GHG Protocol](https://img.shields.io/badge/GHG_Protocol-Corporate_·_Scope_3_·_LSR_2026-04BF62?style=flat-square)
![IPCC AR6](https://img.shields.io/badge/IPCC_AR6-GWP--100-04BF62?style=flat-square)
![CSRD](https://img.shields.io/badge/CSRD-ESRS_E1-04BF62?style=flat-square)
![SBTi](https://img.shields.io/badge/SBTi-Net--Zero-04BF62?style=flat-square)
![PCAF](https://img.shields.io/badge/PCAF-Financed_Emissions-04BF62?style=flat-square)
![ISO 14064-1](https://img.shields.io/badge/ISO-14064--1-04BF62?style=flat-square)

</div>

---

I build high-precision, GHG Protocol-aligned calculation infrastructure. I'm the architect of
[GreenCalculus](https://greencalculus.com) — the traceable reference layer for corporate carbon
accounting, where every result resolves to a published emission factor and a named standard.

## What I'm building

**[GreenCalculus.com](https://greencalculus.com)** — a carbon-calculator platform mapped against 16 active global standards, where the math is built to be checked, not just trusted.

- **Master Brain data layer** — a single, versioned, parity-tested source of truth for every emission factor, spanning IEA 2026 grid factors, DEFRA / DESNZ 2025, EPA eGRID, the ICE database, and AR6 + AR5 GWP values. The same factor feeds every calculator and the underlying API, so the numbers can't disagree with themselves.
- **Calculation engine architecture** — Vanilla JS, zero dependencies, modern CSS `@layer`, fluid `clamp()` typography, JetBrains Mono with `tabular-nums` for numerical stability.
- **Structured data** — `WebApplication`, `Dataset`, `HowTo`, and `Article` JSON-LD across every calculator for machine-readable provenance.
- **An auditable trust layer** — every calculator is backed by a methodology page and version-tracked references, with each value change logged in a public changelog.

## How I think about carbon math

The discipline is small; the principles are what matter.

- **Traceability over trust.** A number a sustainability lead can hand to an auditor — who can then follow it all the way back to the source factor and the standard — beats a number that's merely "close."
- **One source of truth.** Factors live in one versioned store, never copied into the calculators that consume them. A value change is a tracked, auditable event, not a find-and-replace.
- **Fail-soft, never wrong-but-plausible.** An unrecognised input degrades visibly. The one outcome a carbon tool must never produce is a confident, wrong answer.

## Open methodology work

I publish formal open-methodology documentation under the GreenCalculus organisation. All standard mappings are CC-BY-4.0 — free to cite, translate, and republish with attribution.

| Repository | Purpose |
|---|---|
| [`greencalculus/greencalculus-standards`](https://github.com/greencalculus/greencalculus-standards) | Open methodology mapping for 16 global GHG accounting standards |
| [`greencalculus/greencalculus-methodology`](https://github.com/greencalculus/greencalculus-methodology) | Formal methodology, emission factor datasets, GHG Protocol alignment docs |
| [`greencalculus/greencalculus-calculator-demo`](https://github.com/greencalculus/greencalculus-calculator-demo) | Open-source, zero-dependency calculator demos — Scope 1 combustion, SBTi targets, FLAG, PCAF financed emissions |

## Standards I work with

The full set of standards that underpin the GreenCalculus platform. Live reference pages on [greencalculus.com/standards](https://greencalculus.com/standards/); open methodology mappings (where published) on GitHub under [`greencalculus/greencalculus-standards`](https://github.com/greencalculus/greencalculus-standards).

### Calculation standards (how to count)

- [GHG Protocol Corporate Standard](https://greencalculus.com/standards/ghg-protocol-corporate-standard/) — 2026 revision
- [GHG Protocol Scope 2 Guidance](https://greencalculus.com/standards/ghg-protocol-scope-2-guidance/) — 2015; revision in progress (consultation closed Jan 2026)
- [GHG Protocol Scope 3 Standard](https://greencalculus.com/standards/ghg-protocol-scope-3-standard/) — 2011; Phase 1 revision update Mar 2026
- [GHG Protocol Land Sector and Removals Standard](https://greencalculus.com/standards/ghg-protocol-land-sector-removals-2026/) — v1.0, effective 1 Jan 2027
- [IPCC 2006 Guidelines for National GHG Inventories](https://greencalculus.com/standards/ipcc-2006-guidelines-national-inventories/) — with 2019 Refinement

### Scientific basis

- [IPCC AR6 — 100-year Global Warming Potentials](https://greencalculus.com/standards/ipcc-ar6/) — AR6 (2021); AR7 timeline still disputed at IPCC

### Verification, assurance, and product-level

- [ISO 14064-1 — organisation-level GHG quantification](https://greencalculus.com/standards/iso-14064-1/) — 2018 (confirmed 2024)
- [ISO 14067 — product carbon footprint](https://greencalculus.com/standards/iso-14067-product-carbon-footprint/) — 2018 (confirmed 2024)
- [ISO 14040 / 14044 — life cycle assessment](https://greencalculus.com/standards/iso-14040-14044-lca/) — foundational LCA framework
- [BS EN 15978 — embodied carbon in buildings](https://greencalculus.com/standards/bs-en-15978-embodied-carbon-buildings/) — EN 15978-1 revision expected 2025–2026

### Disclosure regimes

- [CSRD / ESRS E1 — Climate change](https://greencalculus.com/standards/csrd-esrs-e1/) — ESRS Set 1 as modified by Omnibus I (EU 2026/470)
- [TCFD Recommendations](https://greencalculus.com/standards/tcfd-recommendations/) — disbanded Oct 2023; monitoring with IFRS Foundation

### Target-setting frameworks

- [SBTi Corporate Net-Zero Standard](https://greencalculus.com/standards/sbti-corporate-net-zero-standard/) — v1.2; v2 consultation closed Dec 2025
- [RE100 — Technical Criteria](https://greencalculus.com/standards/re100-technical-criteria/) — 2024 update

### Regulatory factor sets and sectoral regulations

- [UK DEFRA / DESNZ GHG Conversion Factors](https://greencalculus.com/standards/uk-defra-emission-factors/) — 2025 v1
- [EU F-Gas Regulation (EU) 2024/573](https://greencalculus.com/standards/f-gas-regulation-eu-2024/) — in force March 2024; HFC phase-down to 2050

---

## Background

- Lead Systems Architect, GreenCalculus (Singapore)
- Singapore Institute of Technology alumnus
- Professional Guide to Sustainability Reporting (Tinto Group)
- Independent advisor on corporate GHG accounting infrastructure

## Open to

Standards corrections · methodology collaboration · advisory on corporate GHG accounting infrastructure.

- 🌐 [GreenCalculus.com](https://greencalculus.com) — main platform
- 📚 [GreenCalculus on GitHub](https://github.com/greencalculus) — open methodology repos
- 👤 [About](https://greencalculus.com/about/jeremiah-say/) · 💼 [LinkedIn](https://www.linkedin.com/in/jeremiahsay/)
- 📧 jeremiah@greencalculus.com

---

*All open methodology work is published under CC-BY-4.0 — free to cite, translate, and republish with attribution.*
