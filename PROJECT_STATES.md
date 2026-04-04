# CDCF Project States

| | |
|---|---|
| **Version** | v0.1 (draft for community review) |
| **Status** | Working draft — approved for publication pending board review |
| **Scope** | All projects submitted to or hosted within the CDCF ecosystem |
| **Relationship** | Companion document to [CDCF Project Vetting Criteria](https://github.com/CatholicOS/foundation-docs/blob/main/ai-governance/ai-vetting-criteria.md) |

---

## Purpose

This document defines the three states a project may occupy within the CDCF ecosystem, specifies when the vetting framework applies, and clarifies what each state means for contributors, institutions, and the foundation.

The vetting framework was never intended to apply to every project in the repo. Open source communities operate across a spectrum — early experiments, forming projects, and mature projects that represent the organization with institutional confidence. This document makes that spectrum explicit.

---

## What Sets CDCF Apart from Secular Incubators

Frameworks like Apache's incubation process answer technical questions well: Can this be built? Does it serve a documented need? Does it have a community? Can it be implemented at scale? These questions correspond closely to Gate 2 of the CDCF vetting framework.

What secular frameworks do not address is the prior question: *Should the Church use this tool at all?* That is Gate 1. It answers a theological question before an operational one. Together the two gates allow both ecclesial leaders and technical teams to evaluate the same project through the lens appropriate to their responsibility — one asking whether a tool serves human dignity and the Church's mission, the other asking whether it can be deployed responsibly in institutional environments.

This sequence — why before how — is CDCF's differentiator. It is not a layer added on top of technical review. It is the first gate that every project must pass before technical review begins.

The CDCF manifesto states the mission directly: "Our mission is to aggregate, vet, and communalize these gifts." Project states are the operational expression of that mission — they define what each word means in practice.

---

## The Three Project States

### State 1 — Experimental

A project in Experimental state is part of the CDCF ecosystem for the purpose of community collaboration. It has not entered any formal review. It carries no CDCF endorsement or recommendation.

Experimental projects are welcome. They are how the commons grows. A project may remain in Experimental state indefinitely. There is no expectation of progression, no timeline pressure, and no requirement that it ever enter incubation. An Experimental project that never graduates may still generate significant community value.

**What this state means for contributors:** Build, collaborate, iterate. No vetting criteria apply. The project is in the community space.

**What this state means for institutions:** An Experimental project has not been reviewed against CDCF criteria. Institutions evaluating it for deployment should apply their own discernment processes.

**Applicable vetting criteria:** None.

---

### State 2 — Incubating

A project enters Incubating state when it has satisfied all six criteria of Gate 1 of the CDCF vetting framework. Gate 1 evaluates mission alignment, human accountability architecture, transparency of scope, independent validation of claimed capabilities, subgroup performance review, and deployment governance specification.

Incubating status signals that the project has passed the ecclesial threshold — the "why" question — and is under active development toward graduation. It carries the weight of CDCF's theological and institutional review.

Gate 1 criteria are grounded in *Antiqua et Nova* (January 2025), Canon 627, Canon 1609, and two addresses from Pope Leo XIV. They were reviewed and validated by the CDCF board and advisory councils in March 2026.

**What this state means for contributors:** The project has cleared the first gate. Development continues with Gate 2 requirements in view.

**What this state means for institutions:** An Incubating project has satisfied CDCF's theological and mission alignment criteria. It has not yet met full deployment governance requirements. Institutions may evaluate it with that understanding.

**Applicable vetting criteria:** Gate 1 — all six criteria required.

---

### State 3 — Active

A project reaches Active state when it has satisfied Gate 2 of the vetting framework while maintaining full Gate 1 compliance. Gate 2 evaluates documentation sufficient for independent deployment, data stewardship, governance and maintenance processes, and subsidiarity compatibility — the requirement that the project remain configurable at the parish, diocesan, or institutional level without a central authority absorbing local control.

Active status is the CDCF's formal endorsement. It signals that the project can be pointed toward Catholic institutions with confidence — that a director of technology at a diocesan schools office, working without access to the project's authors, could deploy it responsibly within 90 days.

The subsidiarity requirement in Gate 2 draws directly from the CDCF bylaws (Article I, Section 2), which list subsidiarity as a governing organizational principle, and from the CDCF manifesto's translation of Belloc's guild principle: shared infrastructure, local control preserved, no centralized ownership beyond what sustainability requires.

**What this state means for contributors:** The project represents the foundation. Maintenance, version control, vulnerability response, and named accountability are required.

**What this state means for institutions:** An Active project has met CDCF's full theological, operational, and deployment governance criteria. The foundation recommends it for Catholic institutional use.

**Applicable vetting criteria:** Gate 1 (all six) and Gate 2 (both criteria) — all required, Gate 1 must remain satisfied.

---

## State Summary Table

| State | Vetting Applied | CDCF Endorsement | Institutional Recommendation |
|---|---|---|---|
| **Experimental** | None | None | Institutions apply own discernment |
| **Incubating** | Gate 1 (all six criteria) | Theological/mission alignment confirmed | Evaluate with Gate 2 gaps in view |
| **Active** | Gate 1 + Gate 2 (all eight criteria) | Full endorsement | Recommended for institutional deployment |

---

## Project Scope: Beyond AI Tools

The vetting framework was developed in the context of AI tools submitted to the CDCF. The underlying framework is designed for extension to technology projects more broadly — APIs, data repositories, digital infrastructure, and community platforms.

The language of project governance, not AI governance, reflects that scope. AI tools are among the first category of projects reviewed under this framework. They will not be the last.

Current CDCF projects in the ecosystem — BibleGet API, OntoKit, Liturgical Calendar API, Catholic Semantic Canon — each sit at a different point in this spectrum. The project states framework gives each of them a defined position and a clear pathway, without imposing review requirements on work that is still forming.

---

## Relationship to the Vetting Criteria

The [CDCF Project Vetting Criteria](https://github.com/CatholicOS/foundation-docs/blob/main/ai-governance/ai-vetting-criteria.md) document defines all eight criteria in full, with Magisterial grounding, canonical basis, and documented case studies for each. This document defines when those criteria apply.

Read together: the vetting criteria document answers *what* is evaluated. This document answers *when* and *to what*.

---

## An Invitation to Iterate

This is a v0.1 working draft. Every state definition, every criterion boundary, and every institutional recommendation is subject to revision through community input, council review, and pilot experience.

The Ecclesial Advisory Council is the appropriate body to scrutinize the theological and canonical basis for state transitions. The Technical Advisory Council is the appropriate body to pressure-test whether the Gate 2 deployment criteria hold in real institutional environments.

Contributions, challenges, and proposed revisions are welcome via pull request or issue on the [CatholicOS GitHub](https://github.com/CatholicOS).

*Drafted in response to board and advisory council review session, March 2026. Incorporates decisions on project lifecycle, language scope, and the Gate 1 / Gate 2 distinction confirmed during that session.*
