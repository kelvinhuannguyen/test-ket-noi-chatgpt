# Operational Workflow

Use this reference after reading `SKILL.md`. It turns an open-ended trend request into an auditable research pipeline without claiming unverified metrics.

## 1. Input checklist

Capture before research:

- Target country and audience language
- Start and end dates, including the as-of date for an incomplete period
- Number of topics
- Required file type, headers, column order, and filename
- Exclusions, monetization goals, and acceptable risk level

If the user already supplied these fields, do not ask again.

## 2. Evidence ledger

Maintain a working ledger outside the final spreadsheet with:

| Field | Purpose |
| --- | --- |
| Candidate topic | Specific channel/video niche |
| Primary keyword | Best single audience-language query |
| Source | Trends, YouTube, calendar, report, or other public signal |
| Market/property | Country and search property used |
| Observed date | Freshness and partial-period control |
| Signal | Popular, rising, seasonal, recurring, or commercially active |
| Confidence | High, medium, or low with a short reason |
| Caveat | Proxy data, incomplete month, ambiguous intent, or similar |

Do not convert qualitative signals into fabricated numeric search volume.

## 3. Source hierarchy

Use the strongest available sources in this order:

1. Google Trends configured to the target country, requested dates, and YouTube Search.
2. YouTube autocomplete and live search results in the audience language.
3. Recent video traction across multiple channels, interpreted relative to channel size and upload age.
4. First-party or authoritative event calendars, government releases, trade bodies, and platform documentation.
5. Credible industry reports and public trend roundups as corroboration, not as a replacement for platform intent.

For current or future-facing research, browse and record dates. If direct Trends extraction is unavailable, say so and triangulate from public signals; never present a proxy as exact Trends data.

## 4. Candidate generation

Generate more candidates than needed—normally 2–4 times the final count—across:

- Seasonal events and deadlines
- Practical how-to and troubleshooting intent
- Product comparison and buying intent
- Personal finance, career, home, health-adjacent wellness, travel, hobbies, and education
- Recurring annual moments and emerging subcultures

Exclude categories whose primary appeal depends on copyrighted clips, music, celebrity footage, or unlicensed compilations.

## 5. Long-tail transformation

When a seed is broad or crowded, add one or more constraints:

`audience + problem + format + timing + product/category`

Examples:

- `travel` → `carry-on packing for European summer trips`
- `fitness` → `10-minute mobility routine for desk workers`
- `personal finance` → `Roth IRA withdrawal rules explained`

The final topic should imply a repeatable series, not one isolated video.

## 6. Hard gates

Reject a candidate if any gate fails:

- **Demand:** no credible evidence of meaningful or rising interest
- **Specificity:** too broad to express as one clear primary keyword
- **Repeatability:** cannot support multiple long videos and Shorts
- **Production:** requires access, demonstrations, or footage AI cannot responsibly replace
- **Originality:** likely to become templated summaries without new explanation or value
- **Copyright:** depends on third-party video, music, broadcasts, or characters
- **Policy:** high likelihood of harmful, deceptive, sensational, or monetization-limited treatment
- **Business:** lacks a plausible AdSense, affiliate, sponsorship, or digital-product path

For health, finance, legal, elections, and other high-stakes topics, require stronger sourcing, conservative claims, and clear educational framing.

## 7. Internal scoring

Score each surviving candidate from 0–5 on six dimensions:

| Dimension | 0 | 5 |
| --- | --- | --- |
| Demand | Weak or unsupported | Strong multi-signal demand |
| Growth/timing | Declining or mistimed | Rising or well-timed recurring window |
| Opportunity | Dominated and generic | Clear long-tail gap |
| AI production fit | Hard to illustrate originally | Easy to script, narrate, and visualize |
| Monetization | No credible path | Multiple natural revenue paths |
| Safety | High policy/copyright risk | Low risk with original treatment |

Default weighted score:

`25% demand + 15% growth/timing + 20% opportunity + 15% AI fit + 15% monetization + 10% safety`

Use scores for relative ranking only. They are analyst judgments, not platform metrics. Break ties by evidence confidence, then by long-term repeatability.

## 8. Final selection

For every final row:

- Topic and keyword are in the audience language
- Keyword is one natural query, not a comma-separated list
- Topic is concrete enough to guide a content series
- No duplicate or near-duplicate search intent
- Original scripts, commentary, and editing can add clear value
- The concept works in long-form and Shorts
- Monetization does not depend on misleading claims

## 9. Spreadsheet QA

Use the Spreadsheets skill and verify:

- Exact headers, order, and number of columns
- Exact requested row count plus one header row
- Sequential numbering beginning at 1
- No blank, duplicate, or merged data cells
- No hidden columns, extra sheets, formulas, or unverifiable metrics unless requested
- Readable column widths, wrapped text, frozen header, and basic filter when compatible with the brief
- Exact filename and `.xlsx` extension
- Successful reopen/recalculation and visual inspection

## 10. Handoff

Deliver the file and briefly state:

- Market, language, date window, and as-of date
- What signal classes were used
- That no unverified search metrics were reported
- Any material limitation, especially proxy evidence or an incomplete month

Keep methodology and caveats outside the workbook when the user requires an exact three-column schema.
