# Brace Law — Google Ads Growth Strategy
**Practice Areas:** Immigration Law, Family Law | **Markets:** Hamilton, GTAH, Vaughan, Brampton**Goal:** Maximize qualified leads (consultations) at the lowest cost per acquisition

---

## Strategic Diagnosis

The account has a solid foundation — good CTRs, active search demand, and real conversions — but three structural problems are suppressing performance:

1. **Broken measurement** — Smart Bidding cannot optimize what it cannot measure
2. **Budget imbalance** — one campaign gets 91% of spend; others are starved
3. **Missing campaigns** — Family Law is nearly off, Brampton unknown, no Remarketing

Fix measurement first. Everything else depends on it.

---

## Phase 1 — Fix the Foundation (Week 1–2)

### Step 1: Repair Conversion Tracking
Priority above everything else. Do this before changing any bids or budgets.

- Identify the 2 inactive tags in Tools > Conversions
- Re-install via Google Tag Manager or hardcode on thank-you/confirmation pages
- Set up the following conversion actions (if not already):
  - Contact form submission (primary)
  - Phone call from ads (primary)
  - Phone call from website — 60+ seconds (primary)
  - Live chat initiated (secondary)
  - Consultation booking confirmation (primary)
- Verify all tags with Google Tag Assistant before proceeding
- Remove or disable all 6 "no recent conversions" actions that are not salvageable

### Step 2: Add Critical Negative Keywords
Add these account-wide immediately to stop wasting budget:

```
matkowsky
matkowsky immigration
free immigration
free consultation
DIY immigration
immigration forms
how to apply
IRCC
government immigration
immigration consultant (if not targeting consultants)
jobs
careers
immigration news
```

Add to a shared negative keyword list and apply to all campaigns.

### Step 3: Migrate Call-Only Ads to Call Assets
- Go to Assets > Call assets
- Add your phone number as a call asset to all active campaigns
- Once applied, pause the Call-Only campaigns
- Deadline: February 2027 — do it now to avoid disruption

---

## Phase 2 — Budget Rebalancing (Week 2–3)

### Current Budget Allocation (Estimated)

| Campaign | Est. Daily Budget | Result |
|---|---|---|
| Immigration Landing Page (GTAH) | ~CA$60/day | Overspending |
| IMM \| Refusals \| Search \| GTAH | ~CA$5/day | Budget-limited |
| Family Law GTAH | ~CA$2/day | Nearly invisible |
| Family Law (Vaughan) | CA$0 | Paused |

### Recommended Budget Rebalancing

| Campaign | Recommended Daily Budget | Rationale |
|---|---|---|
| Immigration Landing Page (GTAH) | CA$45/day | Reduce — was overspending with +125% cost spike |
| IMM \| Refusals \| Search \| GTAH | CA$25/day | Increase — best cost-per-conversion, budget-limited |
| Family Law GTAH | CA$15/day | Increase — high-value practice area, nearly zero spend |
| Family Law (Vaughan) | CA$15/day | Re-enable — active market, zero coverage now |
| Brampton (pending review) | CA$10/day | Reinstate if targeting active |

**Total: ~CA$110/day (~CA$3,300/month)** vs. current ~CA$65/day

If budget cannot increase, reallocate from Immigration Landing Page to the underserved campaigns.

---

## Phase 3 — Campaign Structure Rebuild (Week 3–6)

### Recommended Campaign Architecture

```
IMMIGRATION LAW
├── IMM | General Search | Hamilton
│   └── Ad Groups: immigration lawyer hamilton, immigration lawyer, lawyer near me
├── IMM | General Search | Toronto/GTAH
│   └── Ad Groups: immigration lawyer toronto, immigration lawyer GTA
├── IMM | Refusals & Appeals | GTAH
│   └── Ad Groups: refused immigration, immigration refusal appeal, immigration appeal lawyer
├── IMM | Spousal/Family Sponsorship | GTAH
│   └── Ad Groups: spousal sponsorship, family sponsorship canada, bring family to canada
├── IMM | Work Permits | GTAH
│   └── Ad Groups: work permit lawyer, LMIA lawyer, closed work permit
└── IMM | Citizenship | GTAH
    └── Ad Groups: citizenship application lawyer, canadian citizenship help

FAMILY LAW
├── FAM | Divorce & Separation | Vaughan
├── FAM | Divorce & Separation | Brampton
├── FAM | Child Custody | GTAH
└── FAM | Property Division | GTAH

REMARKETING
└── RMK | Website Visitors | All Practice Areas
    └── Audience: visited site but did not convert (30-day window)
```

### Why This Structure

- Separates Hamilton vs. GTAH traffic — Hamilton has its own search behavior ("immigration lawyer hamilton" is a top term)
- Breaks out high-value sub-practice areas (refusals, spousal) that have distinct intent and can be bid differently
- Family law gets proper coverage instead of one underfunded campaign
- Remarketing captures people who visited but didn't convert — typically 3–5x cheaper per lead

---

## Phase 4 — Bid Strategy Optimization (Week 4+)

### Current State
Smart Bidding is active but operating with incomplete data (broken tags). Once tracking is fixed:

### Recommended Bid Strategy by Campaign

| Campaign | Bid Strategy | Target |
|---|---|---|
| IMM General Search | Maximize Conversions → Target CPA | CA$150 target CPA once 30+ conversions |
| IMM Refusals & Appeals | Target CPA | CA$120 (higher-value client) |
| Family Law | Maximize Conversions | Let it learn for 30 days first |
| Remarketing | Target CPA | CA$80 (warmer audience) |

**Do not switch to Target CPA** until each campaign has at least 30 conversions in a 30-day window. Before that, use Maximize Conversions.

### Device Bid Adjustments
Based on current data (computers convert at 55.6% but get only 34.8% of clicks):
- Computers: **+20% bid adjustment**
- Mobile: **-10% bid adjustment**
- Tablets: **-100% bid adjustment** (0% conversions)

### Ad Schedule Bid Adjustments
Based on top bidding signals:
- Weekdays 11AM–7PM: **+15%**
- Weekends 8AM–2PM: **-20%**
- Weekdays before 8AM: **-25%**

---

## Phase 5 — Ad Creative Improvement

### Current Weakness
The account is likely running the same ads across all intent types. Refusal appeal searchers have very different intent than general "immigration lawyer" searchers.

### Ad Copy Principles for Law Firm

Every ad must include:
1. **Specific practice area** — not just "immigration lawyer"
2. **City/region** — "Serving Hamilton & GTA"
3. **Trust signal** — years of experience, consultations offered, success rate
4. **Clear CTA** — "Book a Free Consultation Today"

### Example Ad Sets by Campaign

**IMM | General Search | Hamilton**
```
Headline 1: Hamilton Immigration Lawyer
Headline 2: Free Consultation — Call Today
Headline 3: Trusted Immigration Law Firm
Description 1: Experienced immigration lawyers serving Hamilton & the GTA. Book your free consultation.
Description 2: Visa applications, sponsorships, work permits & more. Call Brace Law today.
```

**IMM | Refusals & Appeals**
```
Headline 1: Immigration Refusal? We Can Help
Headline 2: Appeal Your Immigration Refusal
Headline 3: Experienced Refusal Lawyers — GTAH
Description 1: Refused a visa, PR, or permit? Brace Law handles immigration appeals across the GTA.
Description 2: Don't give up after a refusal. Our lawyers fight for your case. Free consultation.
```

**Family Law**
```
Headline 1: Family Law Lawyer — Vaughan
Headline 2: Divorce, Custody & Separation
Headline 3: Compassionate. Experienced. Local.
Description 1: Navigating separation or custody? Brace Law provides trusted family law advice in Vaughan.
Description 2: Protecting your family's future. Book a confidential consultation today.
```

### Ad Assets to Add/Improve
- **Sitelinks:** About Us, Practice Areas, Free Consultation, Contact
- **Callouts:** Free Consultation, Serving Hamilton & GTA, 10+ Years Experience, Same-Day Appointments
- **Call asset:** Phone number on all campaigns
- **Location asset:** Link to Google Business Profile
- **Image assets:** Professional law office photos (for Display/PMax if added later)

---

## Phase 6 — Remarketing (New)

This is currently missing from the account and is a high-ROI opportunity.

### Setup
1. Ensure Google Ads tag is firing on all pages of bracelaw.ca
2. Create audiences:
   - All website visitors (30 days)
   - Visited contact/consultation page but did not submit (14 days)
   - Visited specific practice area pages (30 days)
3. Create a Search remarketing campaign (RLSA) targeting all visitors with slightly higher bids
4. Create a Display remarketing campaign for brand awareness to past visitors

### Expected Impact
Remarketing audiences typically convert at **3–5x** the rate of cold traffic at **30–50% lower CPA**.

---

## Phase 7 — Landing Page Alignment

Ads are only as good as the page they send traffic to. Each campaign should send traffic to a page that matches the ad's intent.

| Campaign | Landing Page Should Include |
|---|---|
| IMM General (Hamilton) | "Hamilton Immigration Lawyer" in H1, local phone number, map, form |
| IMM Refusals | "Immigration Refusal Appeal" headline, specific refusal types handled, success examples |
| Family Law Vaughan | Vaughan-specific content, family law practice areas listed, local trust signals |
| All campaigns | Clear CTA above the fold, mobile-optimized, fast load time (<2s), phone number clickable |

Run a landing page speed test. If pages load in over 3 seconds on mobile, that alone can account for 50%+ of dropped leads.

---

## 90-Day KPI Targets

| Metric | Current (Mar) | 90-Day Target |
|---|---|---|
| Monthly Conversions | ~11 (extrapolated) | 35+ |
| Cost per Conversion | CA$181 | CA$120 or less |
| Optimization Score | 54.8% | 80%+ |
| Active Conversion Tags | 2 of 10 | 5+ recording |
| Active Campaigns | 3 | 6–7 |
| Monthly Spend | ~CA$2,000 | CA$3,000–3,500 |

---

## 30-Day Quick Win Checklist

- [ ] Fix 2 inactive conversion tags
- [ ] Remove/disable 6 unused conversion actions
- [ ] Add negative keywords (matkowsky, free, DIY, government, etc.)
- [ ] Add desktop bid adjustment +20%
- [ ] Add tablet exclusion -100%
- [ ] Increase IMM | Refusals budget from ~CA$5 to CA$25/day
- [ ] Re-enable Family Law (Vaughan) campaign
- [ ] Add call assets to all campaigns
- [ ] Add ad schedule bid adjustments
- [ ] Audit Brampton campaign status
- [ ] Begin migration away from Call-Only ads
