# Signal Detection & Measurement

## Purpose

Knowing what signals exist is not enough. For EII to function in 
practice, ecosystem operators need to know two additional things 
for each signal:

- **Where and how to detect it** — the sources, methods, and 
  touchpoints through which a signal can be observed or captured
- **How to measure it** — the KPIs and metrics that confirm the 
  signal is real, indicate its strength, and track how it 
  changes over time

This document is the operational companion to the 
[Actor Taxonomy](../00-foundation/actor-taxonomy.md). Where the 
taxonomy defines what signals each actor generates, this document 
defines how to find and measure them in practice.

---

## How to Read This Document

For each actor type, this document will provide:

**Detection** — where the signal lives and how to surface it:
- Primary sources (databases, events, interviews, platforms...)
- Detection methods (surveys, observation, data feeds, 
  structured conversations...)
- Frequency (is this a continuous signal, periodic, or event-driven?)
- Who is best positioned to detect it

**Measurement** — how to know the signal is real and track it:
- Relevant KPIs and metrics
- Baseline indicators
- How to track change over time

---

## Status

This document is under active development. Signal detection and 
measurement entries will be added actor by actor, starting with 
the actors most central to EII operations.

Contributions are welcome — especially from practitioners who 
have direct experience detecting and measuring ecosystem signals 
in specific contexts. See [CONTRIBUTING.md](../CONTRIBUTING.md) 
for how to contribute.

---

## Entries

*To be developed. Entries will follow the actor sequence 
in the Actor Taxonomy.*

### 1. Public Entities
*Coming soon*

### 2. Universities
*Coming soon*

### 3. Coworking Spaces
*Coming soon*

### 4. Startup Event Organisers
*Coming soon*

### 5. Incubators
*Coming soon*

### 6. Accelerators
*Coming soon*

### 7. Tech Parks
*Coming soon*

### 8. Investors
*Coming soon*

### 9. Banks
*Coming soon*

### 10. Mentors
*Coming soon*

### 11. Media
*Coming soon*

### 12. Chambers of Commerce
*Coming soon*

## 13. Corporates

*Large companies with significant impact on the national economy 
and/or with active open innovation plans or strategies.*

---

### What signals to look for

The most valuable corporate signal for EII purposes is 
**pilot and partnership readiness** — identifying which 
companies are actively open to working with startups, 
at what stage, and in what problem domains. This signal 
is rarely stated directly. It must be inferred from 
a combination of sources across three tiers.

---

### Tier 1 — Structured / machine-readable sources

These sources offer the highest reliability and are 
most suitable for automated ingestion at scale.

**Public procurement databases**
National and supranational procurement portals publish 
RFIs, innovation-specific tenders, and pre-commercial 
procurement notices. These are explicit demand signals 
with structured data — a company publishing an 
innovation procurement notice has already passed 
internal approval to engage externally.
*Examples: TED (EU-wide), national equivalents 
in most countries.*

**Funding and grant databases**
When a corporate joins a publicly funded innovation 
project, the project description names the problem 
they are trying to solve. This is one of the most 
underutilised signal sources in most ecosystems.
*Examples: Horizon Europe, EIC Accelerator, 
national innovation agency databases.*

**Company filings**
Annual reports, sustainability reports, and investor 
day transcripts are structured enough to parse at 
scale. Innovation priorities and technology gaps 
are often named explicitly — particularly in 
sustainability and R&D sections.

**Patent filings**
Patent activity reveals where a company is actively 
building capability. Gaps in their patent landscape — 
areas adjacent to their core where they are not filing 
— often indicate where they would prefer to partner 
rather than build internally.

**Corporate venture capital (CVC) portfolio 
announcements**
When a corporate invests in a startup solving a 
specific problem, that is a high-confidence, 
public signal of strategic intent. CVC activity 
is one of the most reliable indicators of genuine 
openness to external innovation in a domain.

---

### Tier 2 — Semi-structured / scrapable sources

These sources require more processing but offer 
high frequency and high intent quality.

**Job postings**
One of the highest-signal sources available. 
A company posting multiple roles around a 
specific capability gap is signalling an 
unmet need — and often an openness to 
external solutions while internal capacity 
is being built. High frequency and high 
intent quality.
*Sources: LinkedIn, Indeed, company career pages.*

**Press releases and news**
Corporate innovation announcements, partnership 
deals, and pilot program announcements signal 
what a company has just validated and wants 
more of. A recently announced pilot in a domain 
is strong evidence of ongoing openness.

**Corporate accelerator and challenge program pages**
The brief that a corporate writes for an 
innovation challenge is essentially a structured 
problem statement. These are among the most 
explicit and actionable demand signals available — 
and most ecosystems do not systematically 
collect them.

**Event participation data**
Who sponsors, speaks at, or sends delegates 
to innovation-focused conferences and events 
is a reliable indicator of active engagement 
intent — not passive interest.

**LinkedIn company pages and employee posts**
Innovation leads and strategic directors 
talking publicly about problems they are 
trying to solve are providing unfiltered 
demand signals. This source requires 
systematic monitoring rather than 
one-off searches.

---

### Tier 3 — Unstructured / harder to capture

These sources require more sophisticated processing 
but carry high-quality signal when extracted.

**Podcast and video content**
Corporate innovation leads on panels, podcasts, 
and webinars often speak more candidly about 
real challenges than in any official communication. 
Rich signal — but requires transcription and 
natural language processing to extract at scale.

**Industry association reports and working 
group outputs**
PDF-heavy and inconsistently structured, but 
high-quality signal when parsed. Working group 
outputs in particular often reflect collective 
corporate demand that no individual company 
has stated publicly.

**RFI/RFP documents**
Often attached as PDFs in procurement portals. 
The full document typically contains far richer 
problem framing than the portal summary — 
worth extracting systematically.

---

### Who inside a corporate holds the signal

The most accurate internal sources are:

- **Strategic venture directors and open 
  innovation leads** — closest to the 
  actual innovation appetite and 
  partnership readiness
- **Chief Innovation Officers and CIOs** — 
  strategic direction and technology gap awareness
- **Business unit leads** — operational 
  problem owners, often the most specific 
  about what they actually need
- **CVC managers** — clearest signal on 
  domains where the corporate is prepared 
  to commit resources

Note: official communications (PR, marketing) 
are typically the least reliable source. 
The signal quality improves significantly 
when you reach the people with operational 
responsibility rather than communications 
responsibility.

---

### Intent scoring

Not all corporate signals carry equal weight. 
A viable EII implementation must distinguish 
between levels of intent:

| Intent level | Description | Signal indicators |
|---|---|---|
| **Passive exploration** | Aware of startups, no active engagement | Attends events, follows innovation media |
| **Active interest** | Engaging in conversations, evaluating options | Joins accelerator programs, responds to RFIs |
| **Pilot readiness** | Has budget, mandate, and internal champion | Publishes innovation challenges, joins funded projects, active procurement |
| **Committed partner** | Has completed at least one pilot, seeking more | Announces partnerships, CVC investments, repeat program participation |

The goal of the collection layer is to identify 
corporates at **pilot readiness** level or above — 
these are the signals most immediately actionable 
for startups.

---

### Normalising signals into a common demand schema

Signals from different sources must be normalised 
into a consistent format to be useful across 
the ecosystem. The minimum viable demand schema 
for a corporate signal includes:

- **Problem domain** — the area where the need exists
- **Capability gap** — what specifically they 
  cannot or do not want to build internally
- **Stage of intent** — using the scoring above
- **Company profile** — size, sector, geography, 
  innovation maturity
- **Signal source and date** — for freshness assessment
- **Confidence score** — derived from source 
  tier and corroboration across multiple sources

---

### Recommended starting point

For ecosystems beginning to build this layer, 
the highest signal-to-noise starting point is:

1. **Job postings** — high frequency, 
   high intent, easy to collect
2. **Procurement databases** — structured, 
   explicit demand, publicly available
3. **Corporate accelerator and challenge briefs** 
   — explicit problem statements, often underutilised

These three sources alone, systematically 
collected and normalised, would represent a 
significant leap forward for most ecosystems.

---

### KPIs for this signal type

| KPI | What it measures |
|---|---|
| Number of corporates with active signals | Volume of identified pilot-ready companies |
| Signal freshness | Average age of signals in the system — older than 6 months degrades reliability |
| Intent level distribution | Share of corporates at each intent level |
| Domain coverage | Which problem domains have strong corporate signal vs. gaps |
| Signal corroboration rate | Share of corporates identified from 2+ independent sources — higher corroboration = higher confidence |
| Conversion rate | Share of corporate signals that result in actual startup connections — the ultimate validation |

### 14. Donors & Development Financiers
*Coming soon*

### 15. New Entrepreneurs
*Coming soon*

### 16. Experienced Entrepreneurs
*Coming soon*

### 17. Entrepreneurial Associations
*Coming soon*

### 18. Intellectual Property Registration Entity
*Coming soon*

### 19. Professional Service Providers
*Coming soon*

### 20. Industry Associations
*Coming soon*

### 21. International Companies Investing in the Country
*Coming soon*

### 22. Online Platforms & Portals
*Coming soon*

### 23. Collaborative Initiatives
*Coming soon*
