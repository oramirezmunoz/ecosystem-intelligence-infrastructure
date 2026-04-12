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

*City, regional, and national bodies with competencies and 
responsibilities to develop the innovation and entrepreneurship 
ecosystem.*

---

### What signals to look for

The most valuable public entity signal for EII purposes is 
**genuine commitment to ecosystem development** — identifying 
which institutions have not just announced intentions but have 
specific budgets, plans, and responsible parties in place. 
Political announcements without these three elements are 
noise, not signal.

A secondary but equally important signal is **resource 
availability** — open calls, funded programs, procurement 
opportunities, and policy changes that are immediately 
actionable for other ecosystem actors.

---

### Tier 1 — Structured / machine-readable sources

**Government budget documents and appropriations**
The most reliable commitment signal available. When a 
public entity allocates a specific budget line to 
innovation and entrepreneurship ecosystem development, 
that is a behavioural signal that outweighs any 
political announcement. Budget documents are public 
in most jurisdictions and structured enough to 
parse systematically.

**Official tenders and procurement portals**
Public procurement notices for innovation-related 
services, ecosystem programs, and support 
infrastructure are explicit, time-bound demand 
signals with structured data. Pre-commercial 
procurement and innovation partnerships are 
particularly relevant.
*Examples: TED (EU-wide), national procurement 
portals in most countries.*

**Government program databases and registries**
Official registries of active programs, grants, 
and support instruments. These represent 
committed, funded signals — not proposals 
or intentions.
*Examples: national innovation agency program 
catalogues, regional development fund registries, 
EU structural fund databases.*

**Parliamentary and legislative records**
New legislation, policy frameworks, and 
parliamentary debates signal the direction 
of institutional priorities — often 6 to 
18 months before they translate into 
funded programs.

---

### Tier 2 — Semi-structured / scrapable sources

**Official policy documents and strategy papers**
National and regional innovation strategies, 
smart specialisation strategies, and economic 
development plans. These name priorities 
explicitly — but must be cross-referenced 
with budget data to distinguish genuine 
commitments from aspirational documents.

**Government portal announcements and news**
Official communication channels — ministry 
websites, agency newsrooms, press releases. 
Useful for tracking new program launches, 
deadline announcements, and policy changes. 
High frequency but variable reliability — 
always cross-reference with budget data.

**Annual and performance reports**
Program outcome reports, agency annual 
reports, and audit publications. These 
are among the most underutilised signal 
sources — they reveal what is actually 
working, what is being discontinued, 
and where gaps exist in the current 
support landscape.

**Coalition and partnership announcements**
When a city joins an international innovation 
network, a region signs an MOU with a 
private actor, or a national agency 
co-funds a program with industry — 
these are strong behavioural signals 
of genuine commitment that go beyond 
political statements.
*Examples: membership in EU innovation 
networks, bilateral cooperation agreements, 
public-private co-funding announcements.*

**Event participation and convening activity**
Which public entities convene, sponsor, 
or send senior representation to 
ecosystem events is a reliable 
indicator of active engagement — 
particularly when the same entity 
appears consistently over time.

---

### Tier 3 — Unstructured / harder to capture

**Political speeches and public statements**
Useful for early directional signals — 
what politicians are talking about 
today often becomes policy in 12 to 
24 months. Requires consistent 
monitoring and cross-referencing 
with budget and legislative signals 
to assess credibility.

**Audit and evaluation reports**
Independent evaluations of public programs 
are PDF-heavy and inconsistently published, 
but carry high-quality signal when parsed — 
particularly for understanding what 
instruments have failed and what 
gaps remain unaddressed.

**Informal intelligence from intermediaries**
Ecosystem operators, chambers of commerce, 
and industry associations often have 
direct relationships with civil servants 
and agency directors. Their reading of 
institutional priorities is frequently 
more accurate than any official 
document — but requires structured 
collection through trusted intermediary 
relationships.

---

### Who inside a public entity holds the signal

The answer varies significantly by level:

**At national level**
- Ministry officials and senior civil servants 
  responsible for innovation policy — hold 
  the strategic direction signal
- National innovation agency directors and 
  program managers — hold the operational 
  signal closest to implementation
- Budget office officials — hold the 
  commitment signal

**At regional level**
- Regional development agency directors 
  and program officers — typically the 
  most operationally accurate source
- Regional government economic development 
  leads — strategic direction

**At city level**
- City economic development officers — 
  often the most direct and accessible 
  source of actionable signal
- Mayor's office innovation leads — 
  where these roles exist, they hold 
  the highest-priority signals

**Universal principle:** the civil servant 
or program officer with operational 
responsibility for a specific instrument 
is almost always a more accurate signal 
source than the political leader announcing 
it. Political announcements set direction — 
operational staff determine what actually 
gets implemented.

---

### Commitment vs. announcement: the critical distinction

The single most important analytical task 
when processing public entity signals is 
distinguishing genuine commitment from 
political positioning. A reliable 
commitment signal requires all three 
of the following:

1. **Specific budget allocation** — a named 
   budget line, not a general aspiration
2. **Defined plan or instrument** — a specific 
   program, tender, or policy mechanism, 
   not a strategy document
3. **Named responsible party** — an 
   identifiable person or unit with 
   accountability for delivery

Announcements that lack any of these three 
elements should be classified as directional 
signals only — useful for anticipating 
future instruments but not actionable 
in the near term.

---

### Intent scoring

| Intent level | Description | Signal indicators |
|---|---|---|
| **Directional** | Political intent stated, no operational follow-through yet | Strategy documents, speeches, policy frameworks without budget |
| **Planning** | Budget allocated, instrument under design | Budget line exists, tender preparation underway |
| **Active** | Instrument live, accepting applications | Open calls, active procurement, running programs |
| **Mature** | Track record of delivery, recurring commitment | Multi-year programs, performance reports published, renewed budget cycles |

The goal of the collection layer is to identify 
public entities at **Active** level or above — 
these are the signals most immediately actionable 
for other ecosystem actors seeking support, 
partnerships, or funding.

---

### Normalising signals into a common demand schema

The minimum viable schema for a public entity 
signal includes:

- **Instrument type** — grant, tender, 
  policy, regulatory change, program
- **Target actor types** — who the 
  instrument is designed to serve
- **Development phase relevance** — 
  which Startup Commons phases 
  this instrument addresses
- **Budget and scale** — where available
- **Geographic scope** — city, regional, 
  national, supranational
- **Timeline** — open dates, deadlines, 
  program duration
- **Commitment level** — using the 
  scoring above
- **Signal source and date** — 
  for freshness assessment

---

### Recommended starting point

For ecosystems beginning to build this layer, 
the highest signal-to-noise starting point is:

1. **Official procurement portals** — 
   structured, explicit, time-bound
2. **Program databases and open calls** — 
   immediately actionable for other actors
3. **Budget documents** — the most reliable 
   commitment signal available

These three alone, systematically monitored, 
would give any ecosystem operator a 
significantly more accurate picture of 
public entity activity than currently 
exists in most ecosystems.

---

### KPIs for this signal type

| KPI | What it measures |
|---|---|
| Number of active instruments by level | Volume of live, actionable support across city / regional / national |
| Commitment score distribution | Share of signals at each intent level — directional vs. active |
| Budget coverage by development phase | Which Startup Commons phases are well-funded vs. underserved |
| Instrument freshness | Average age of signals — policy landscapes shift and stale data misleads |
| Geographic coverage | Which territories have strong public entity signal vs. gaps |
| Utilisation rate | Share of identified instruments actually accessed by ecosystem actors — gap between availability and awareness |

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
