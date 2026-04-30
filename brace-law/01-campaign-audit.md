# Brace Law — Google Ads Campaign Audit
**Account:** jurgena@bracelaw.ca | **Period:** Mar 1–25, 2026 | **Audited:** Apr 30, 2026

---

## Account-Level Metrics

| Metric | Value |
|---|---|
| Clicks | 345 |
| Impressions | 4,870 |
| CTR | 7.08% |
| Conversions | 9.00 |
| Cost | CA$1,630 |
| Cost per Conversion | CA$181.11 |
| Optimization Score | 54.8% |

---

## Critical Issues (Fix Immediately)

### 1. 2 Inactive Conversion Tags
- Smart Bidding cannot optimize for leads it cannot see
- Every dollar spent while tags are broken is wasted optimization data
- **Action:** Go to Tools > Conversions > identify inactive tags > reinstall via GTM or site code > verify with Google Tag Assistant

### 2. 6 Conversion Actions with No Recent Conversions
- These are likely old, outdated, or pointing to pages no longer in use
- They dilute your conversion data and confuse Smart Bidding
- **Action:** Audit each one — delete or disable any not actively firing

### 3. Optimization Score: 54.8%
- Below average; driven largely by broken conversion tracking and budget constraints
- Will improve automatically once tracking is fixed

---

## Campaign-Level Issues

| Campaign | Status | Spend (Mar) | Clicks | Conv | Issue |
|---|---|---|---|---|---|
| Immigration Landing Page (GTAH) | Active | CA$1,489.23 | 319 | 7.00 | Overspending — cost up +125.96% vs prior period |
| IMM \| Refusals \| Search \| GTAH | Eligible (Limited) | CA$115.99 | 22 | 1.00 | Budget-limited — underfunded despite strong results |
| Family Law GTAH - Landing Page | Active | CA$23.80 | 4 | 1.00 | Nearly zero budget allocation |
| Family Law (Vaughan) | Paused | CA$0 | 0 | 0 | Entire campaign off |
| Brampton (unknown) | Unknown | — | — | — | Status cut off — needs review |

### Budget Concentration Problem
- 91% of spend (CA$1,489 / CA$1,630) is concentrated in a single campaign
- The IMM | Refusals campaign costs CA$115.99 per conversion vs. CA$212.75 for the main campaign — better efficiency but getting starved

---

## Conversion Tracking Status

| Status | Count |
|---|---|
| Tag inactive (broken) | 2 |
| Unverified | 0 |
| No recent conversions | 6 |
| Recording conversions | 2 |

Only **2 out of 10** conversion actions are confirmed working. This is the root cause of poor Smart Bidding performance.

---

## Device Performance

| Device | Cost Share | Click Share | Conversion Share |
|---|---|---|---|
| Mobile | 55.5% | 64.9% | 44.4% |
| Computer | 44.4% | 34.8% | 55.6% |
| Tablet | 0.0% | 0.3% | 0.0% |

**Desktop converts at a higher rate** despite getting fewer clicks. Mobile is over-represented in spend relative to its conversion output.

---

## Top Bidding Signals (Smart Bidding)

Positive signals (Google increasing bids):
- Desktop + Weekdays 11AM–7PM
- Query: "immigration lawyer hamilton" + Mobile

Negative signals (Google reducing bids):
- Location: Toronto + Weekdays before 8AM
- Time: Weekends 8AM–2PM

---

## Top Search Terms

- immigration lawyer
- immigration lawyer hamilton
- immigration lawyer toronto
- free consultation immigration lawyer
- immigration appeal lawyer
- matkowsky immigration law *(competitor — negative keyword needed)*
- free immigration consultant toronto
- immigration consultant

---

## Top Keywords by Spend

| Keyword | Cost | Clicks | CTR |
|---|---|---|---|
| immigration lawyer | CA$1,368.06 | 290 | 7.28% |
| immigration appeal lawyer | CA$115.99 | 22 | 4.72% |

---

## Deprecation Warning

**Call-Only ads are being deprecated** — must migrate to call assets by **February 2027**.
Use the "Fix it" button in the Google Ads banner to begin migration.
