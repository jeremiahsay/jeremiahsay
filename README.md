<div align="center">

# Jeremiah Say

### Software developer and data scientist · Singapore

**I build sites that turn public records into sourced, checkable answers.**
If a number can't be traced to its source, it doesn't ship.

[GreenCalculus](https://greencalculus.com) · [Numbers.sg](https://numbers.sg) · [Who Actually Makes](https://whoactuallymakes.com) · [PerBowl](https://perbowl.com) · [GraciousQuotes](https://graciousquotes.com) · [Toggle9](https://toggle9.com) · [QuitWithNerd](https://quitwithnerd.com)

[LinkedIn](https://www.linkedin.com/in/jeremiahsay/) · [ORCID](https://orcid.org/0009-0009-2025-7691) · [Wikidata](https://www.wikidata.org/wiki/Q140289441)

</div>

---

## What I run

Each site has a page about my role there: what I check, how I check it, and where to report a mistake.

| Site | Go here if you want to… | What it is | My page there |
|---|---|---|---|
| **[GreenCalculus](https://greencalculus.com)** | find a carbon emission factor and its source | A database and API of carbon emission factors, each traced to its primary publication, with calculators that show where every number comes from. | [Founder & Lead Systems Architect](https://greencalculus.com/about/jeremiah-say/) |
| **[Numbers.sg](https://numbers.sg)** | check a Singapore rate, CPF figure or tax amount | Singapore's money numbers (T-bills, Savings Bonds, fixed deposits, CPF, stamp duty, income tax) taken from the agency or bank that publishes them, each with the time it was checked. The calculators are tested against the agency's own worked examples every time the page is built. | [Editor](https://numbers.sg/about/jeremiah-say/) |
| **[Who Actually Makes](https://whoactuallymakes.com)** | learn who really makes a store brand | Store brands and everyday products traced to the company and factory behind them through public records, with the proof, a stamp showing how sure the answer is, and a re-check date. | [Founder & editor](https://whoactuallymakes.com/about/) |
| **[PerBowl](https://perbowl.com)** | learn who makes your dog or cat food | Pet food brands traced to the companies and plants behind them, with FDA inspection and recall records and free same-day recall alerts. | [Founder & editor](https://perbowl.com/about/jeremiah-say/) |
| **[GraciousQuotes](https://graciousquotes.com)** | check who really said a quote | A quotes site I started in February 2020. My main job there is checking who really said each quote, showing the source, and logging corrections in public. | [Founder & editor](https://graciousquotes.com/about/jeremiah-say/) |
| **[Toggle9](https://toggle9.com)** | use a calculator that shows its working | Free calculators and tools. No sign-up, and each tool is dated with when I last checked it against its sources. | [Creator](https://toggle9.com/about/jeremiah-say/) |
| **[QuitWithNerd](https://quitwithnerd.com)** | get help quitting smoking or vaping | My personal site, started in June 2019, 19 days after my last cigarette, following 17 years of smoking. Guides to quitting and staying quit, written from my own experience, with the research and official sources linked. | [Founder & editor](https://quitwithnerd.com/about/) |

The first six are published by **[Numbers Publishing Pte. Ltd.](https://numbers.sg/company/)**, a Singapore private company (UEN 202500357K) that I own and run. You can look it up by its UEN in ACRA's business registry. No bank, brand, advertiser or investor owns any part of it. QuitWithNerd is a personal site I run myself.

## The rule they share

- **Sourced, or it doesn't go up.** Every factor, quote attribution, maker match or formula points back to where it came from.
- **Doubt is shown, not hidden.** A shaky attribution gets an honest label, a maker answer carries a stamp saying how sure it is, a name match stays a lead until I've read the record, and an unrecognised input fails visibly instead of returning a confident wrong answer.
- **A person decides, scripts fetch.** Scripts pull government lists and agency figures on a schedule and keep dated copies. I read the record behind an answer before it goes up, and again on its re-check date.
- **Mistakes are fixed in public.** Corrections and changes are logged on each site, with dates.
- **Interests are disclosed.** For example, I hold Singapore T-bills and Savings Bonds, bought on the same terms as anyone else, and Numbers.sg has no referral or affiliate deals.
- **Machine-readable provenance.** Structured data (JSON-LD) on every page says who made it, what it's based on and when it was last checked.

## Open work

Most of what I publish openly is under the [GreenCalculus organisation](https://github.com/greencalculus):

| Repository | What it is |
|---|---|
| [`greencalculus-benchmark`](https://github.com/greencalculus/greencalculus-benchmark) | How wrong are LLMs about emission factors, and how often do they name the wrong source? Scored against sourced ground truth. |
| [`gwp-basis-check`](https://github.com/greencalculus/gwp-basis-check) | Finds warming-potential tables that contradict the IPCC assessment report they name. |
| [`greencalculus-calculator-demo`](https://github.com/greencalculus/greencalculus-calculator-demo) | Zero-dependency demos of production carbon calculators: Scope 1 combustion, SBTi targets, FLAG, PCAF, CBAM. |
| [`greencalculus-mcp`](https://github.com/greencalculus/greencalculus-mcp) · [`greencalculus-sdk`](https://github.com/greencalculus/greencalculus-sdk) · [`langchain-greencalculus`](https://github.com/greencalculus/langchain-greencalculus) | Ways to call the emission-factor API from AI agents, Python and JavaScript. |
| [`greencalculus-standards`](https://github.com/greencalculus/greencalculus-standards) · [`greencalculus-methodology`](https://github.com/greencalculus/greencalculus-methodology) · [`greencalculus-open-data`](https://github.com/greencalculus/greencalculus-open-data) | Methodology, standards mapping and source licences, CC-BY-4.0. |

**Open data from Who Actually Makes:** every list behind the site (NHTSA tire plant codes, tire age advice from the makers, and every quote it cites) is free to download as [JSON or CSV under CC BY 4.0](https://whoactuallymakes.com/data/), with stable URLs you can call from code.

<details>
<summary><b>Carbon accounting standards I work with</b></summary>

Live reference pages are on [greencalculus.com/standards](https://greencalculus.com/standards/).

**Calculation:** [GHG Protocol Corporate Standard](https://greencalculus.com/standards/ghg-protocol-corporate-standard/) · [Scope 2 Guidance](https://greencalculus.com/standards/ghg-protocol-scope-2-guidance/) · [Scope 3 Standard](https://greencalculus.com/standards/ghg-protocol-scope-3-standard/) · [Land Sector and Removals](https://greencalculus.com/standards/ghg-protocol-land-sector-removals-2026/) · [IPCC 2006 Guidelines](https://greencalculus.com/standards/ipcc-2006-guidelines-national-inventories/)

**Science:** [IPCC AR6 GWP-100](https://greencalculus.com/standards/ipcc-ar6/)

**Verification and product level:** [ISO 14064-1](https://greencalculus.com/standards/iso-14064-1/) · [ISO 14067](https://greencalculus.com/standards/iso-14067-product-carbon-footprint/) · [ISO 14040/14044](https://greencalculus.com/standards/iso-14040-14044-lca/) · [BS EN 15978](https://greencalculus.com/standards/bs-en-15978-embodied-carbon-buildings/)

**Disclosure:** [CSRD / ESRS E1](https://greencalculus.com/standards/csrd-esrs-e1/) · [TCFD](https://greencalculus.com/standards/tcfd-recommendations/)

**Targets:** [SBTi Corporate Net-Zero](https://greencalculus.com/standards/sbti-corporate-net-zero-standard/) · [RE100](https://greencalculus.com/standards/re100-technical-criteria/)

**Regulatory factor sets:** [UK DEFRA / DESNZ](https://greencalculus.com/standards/uk-defra-emission-factors/) · [EU F-Gas Regulation 2024/573](https://greencalculus.com/standards/f-gas-regulation-eu-2024/)

</details>

## Background

- Software developer, data scientist and data analyst
- Singapore Institute of Technology graduate
- Former maths tutor, which is why my tools show their working
- Professional Guide to Sustainability Reporting (Tinto Group)
- [Wikipedia contributor](https://en.wikipedia.org/wiki/User:Jeremiahsay) on GHG Protocol, IPCC AR6, life-cycle assessment and CSDDD articles

## Get in touch

Corrections, data questions and collaboration are all welcome. I read every message, and reports of a wrong number or a wrong maker are read first. Each site also has its own contact page and public corrections log.

📧 jeremiah@greencalculus.com · 💼 [LinkedIn](https://www.linkedin.com/in/jeremiahsay/) · 🆔 [Wikidata](https://www.wikidata.org/wiki/Q140289441)
