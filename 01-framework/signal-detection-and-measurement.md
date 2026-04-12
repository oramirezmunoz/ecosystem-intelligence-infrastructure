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

*Venture capital firms, angel investors, family offices, 
and other capital providers active in the innovation 
and entrepreneurship ecosystem.*

---

### What signals to look for

The most valuable investor signal for EII purposes is 
**active deployment readiness** — identifying which 
investors are genuinely writing checks now, not just 
visible in the ecosystem. These are fundamentally 
different things, and confusing them is one of the 
most common and costly mistakes in ecosystem intelligence.

Visibility is cheap. Capital commitment is expensive.

The practical test for any investor signal is: 
*"Have they written checks recently, and do market 
participants expect them to write more in the next 
quarter or two?"*

---

### Tier 1 — Structured / machine-readable sources

**Deal databases and investment registries**
Closed deals are the clearest proof of motion. 
Recent investments — closed in the last 3 to 12 
months — are the single most reliable indicator 
of active deployment. What matters is not one 
announcement but a pattern: frequency, recency, 
check size alignment with stated strategy, and 
whether new deals are happening alongside 
follow-ons.
*Examples: Crunchbase, Dealroom, PitchBook, 
national investment registries where available.*

**Fund announcements and close notices**
New fund launched, first close reached, final 
close completed, or fresh capital commitments 
announced — these are structural signals that 
indicate deployment pressure and timeline. 
A firm that has just reached final close 
is under real pacing pressure to deploy.
*Sources: press releases, LP announcement 
notices, regulatory filings where applicable.*

**Regulatory and company filings**
In many jurisdictions, investment vehicles 
file disclosures that reveal fund size, 
portfolio composition, and capital status. 
These are underutilised but highly reliable 
when available.

---

### Tier 2 — Semi-structured / scrapable sources

**Portfolio company announcements**
Portfolio behavior is a rich secondary signal. 
Reserves being deployed, follow-on rounds 
supported, bridge rounds funded, and new 
platform hires all indicate an investor 
actively managing and backing their 
portfolio — which correlates strongly 
with new deployment activity.

**Hiring signals**
Investment associate or principal hiring, 
portfolio talent roles, or geographic 
expansion hiring are strong indicators 
of active deployment intent. A firm 
hiring deal-facing staff is preparing 
to do more deals.
*Sources: LinkedIn, company career pages.*

**Accelerator and program partnerships**
Formal partnerships with accelerators, 
corporate innovation programs, and 
ecosystem operators indicate structured 
deal flow appetite — the investor is 
actively building pipeline, not just 
waiting to be approached.

**Event participation patterns**
Not sponsorship or speaking — those are 
visibility signals. The meaningful signal 
is which investors are repeatedly attending 
founder-facing events, demo days, and 
sector-specific convenings. Attendance 
pattern over time is more reliable 
than any single appearance.

**Partner and principal activity patterns**
Who is visibly taking founder meetings, 
reappearing across warm introductions, 
and showing up in deal-adjacent contexts. 
This requires network observation rather 
than database scraping — but it is a 
high-quality signal when systematically 
collected through ecosystem intermediaries.

---

### Tier 3 — Unstructured / harder to capture

**Founder chatter and market reputation**
Repeated mentions in founder conversations — 
"they moved fast," "they're pricing deals," 
"they passed because their thesis is full" — 
are among the most accurate real-time 
deployment signals available. This 
intelligence travels through trusted 
networks before it appears anywhere 
structured. Systematically collecting 
it requires relationships with active 
founders and accelerator managers.

**Lawyer, co-investor, and angel networks**
Lawyers closing deals, co-investors being 
pulled into rounds, and angels syndicating 
alongside institutional investors often 
know who is truly moving before the 
market does. These intermediaries hold 
some of the most accurate investor 
signals in any ecosystem — and are 
almost never systematically engaged 
as signal sources.

**Data room and process behaviour**
Turnaround speed on requests, depth of 
due diligence questions, and whether 
partners are pulled in quickly during 
a process — these behaviours indicate 
genuine deployment intent versus 
exploratory conversation. Accessible 
only through founder experience, 
but consistently reliable.

**Process and IC behaviour signals**
Who is attending investment committee 
preparation, how fast decisions are 
moving, and whether partners are 
re-engaging after initial meetings — 
these are internal signals that surface 
through ecosystem intermediary 
relationships rather than any 
public source.

---

### Who inside an investment firm holds the signal

The answer depends on what you need to know:

**Managing partner / GP**
Best signal on true conviction, check-writing 
authority, fund pacing, and whether they can 
actually get a deal through IC. The ultimate 
deployment decision sits here.

**Principal**
Often the best real-time read on what is 
live right now. Close enough to active 
processes to know who is moving and 
at what speed. High-accuracy signal 
on current pipeline.

**Associate**
Good for pipeline activity and early 
stage filtering — less reliable on 
whether the firm will ultimately commit.

**CFO / investor relations**
Strongest signal on fund status, reserves 
pressure, and whether the firm is 
structurally in a position to deploy. 
Less externally visible but highly 
accurate on capital availability.

**Platform / community / scout-facing roles**
Useful for access and relationship mapping — 
not reliable for deployment readiness.

**The most accurate combination:**
The deal-owning partner, validated by 
the principal running active processes. 
This combination tells you both whether 
the firm can invest and whether the 
firm is investing now.

Simple decision rule for signal collection:
- Want to know if the firm is active at all 
  → look at recent deal patterns
- Want to know if a specific opportunity 
  is real → reach the principal running 
  the process
- Want to know if the fund has room and 
  urgency → infer from partner behaviour, 
  confirm through ecosystem intermediaries

---

### The visibility trap

The biggest mistake in investor signal 
collection is confusing ecosystem 
visibility with deployment readiness.

An investor can be highly visible — 
publishing content, sponsoring events, 
taking meetings, appearing on panels — 
while barely deploying capital. 
Visibility is a brand activity. 
Deployment is a financial activity. 
The signals for each are completely 
different.

An investor who is truly active leaves 
a specific trail:
- Fresh checks at consistent cadence
- Fast process with real partner engagement
- Consistent market mentions from founders 
  and intermediaries
- Internal people behaving under real 
  pacing pressure

EII signal collection must be designed 
to detect this trail — not to measure 
visibility proxies.

---

### Intent scoring

| Intent level | Description | Signal indicators |
|---|---|---|
| **Inactive** | No recent deployment, fund fully deployed or between funds | No new deals in 12+ months, no fund activity |
| **Monitoring** | Present in ecosystem, not actively deploying | Event attendance, content activity, taking exploratory meetings |
| **Active pipeline** | Building deal flow, conducting due diligence | Associate activity, accelerator partnerships, founder meetings increasing |
| **Deploying** | Writing checks at consistent cadence | Recent deals closed, pattern of new investments, principal-led active processes |
| **Under pressure** | Recent fund close, pacing requirements | New fund announced or closed, hiring, accelerated meeting cadence |

The goal of the collection layer is to identify 
investors at **Deploying** or **Under pressure** 
levels — these are the signals most immediately 
actionable for startups seeking capital.

---

### Normalising signals into a common schema

The minimum viable schema for an investor signal:

- **Fund status** — deploying, between funds, 
  raising, fully deployed
- **Active thesis** — sectors, stages, 
  geographies, business model types
- **Check size range** — minimum and maximum 
  typical ticket
- **Development phase alignment** — which 
  Startup Commons phases they focus on
- **Recent deal cadence** — number of new 
  investments in last 6 and 12 months
- **Deployment intent level** — using 
  the scoring above
- **Signal source and date** — 
  for freshness assessment
- **Confidence score** — higher when 
  corroborated by deal data plus 
  ecosystem intermediary intelligence

---

### Recommended starting point

For ecosystems beginning to build this layer, 
the highest signal-to-noise starting point is:

1. **Deal databases** — recent investment 
   patterns are the most reliable 
   deployment signal available
2. **Fund announcements** — structural 
   signals of deployment pressure 
   and timeline
3. **Ecosystem intermediary intelligence** 
   — accelerator managers, angels, 
   and lawyers who observe investor 
   behaviour directly

These three combined give a significantly 
more accurate picture of who is actually 
deploying than any amount of monitoring 
of investor social media or event presence.

---

### KPIs for this signal type

| KPI | What it measures |
|---|---|
| Number of actively deploying investors | Volume of investors confirmed at Deploying level or above |
| Deal cadence by investor | Frequency of new investments per investor — trend over time |
| Stage and phase coverage | Which Startup Commons phases have strong investor signal vs. funding gaps |
| Thesis freshness | How recently each investor's stated thesis has been validated by actual deals |
| Geographic deployment concentration | Where capital is actually flowing vs. where it is claimed to flow |
| Intermediary corroboration rate | Share of investor signals validated by at least one ecosystem intermediary — higher corroboration = higher confidence |
| Startup connection rate | Share of identified active investors that result in actual founder introductions — the ultimate validation |

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
