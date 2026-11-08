# Gotchas

Failure modes that produce confidently wrong growth advice. Owners move real budget off this pulse, so a plausible-sounding mistake here costs money.

---

## Gotcha: treating higher cost per lead as proof of saturation

**Why it matters:** The same headline can come from changing customer mix or worsening costs within a campaign. The right investigation and budget decision depend on which occurred.

### Bad

```
Paid-social spend and cost per lead rose together. The channel is saturated. Cut the budget.
```

In two comparable periods, the first campaign went from 100 to 50 leads at USD 10 per lead. The second went from 20 to 100 leads at USD 30 per lead. Spend rose from USD 1,600 to USD 3,500 and overall cost per lead rose from USD 13.33 to USD 23.33. Neither campaign's cost per lead changed.

### Good

```
Paid-social cost per lead rose from USD 13.33 to USD 23.33 as the higher-cost campaign
accounted for more leads. Both campaigns' individual costs held steady. Compare their
qualified lead costs before reallocating budget.
```

If costs rise within comparable campaigns, show where and by how much. Without segment detail, report the headline and request the breakdown. See `thresholds.md` for the comparison checks.

## Gotcha: comparing a fresh lead cohort with a mature one

**Why it matters:** A new cohort can appear to convert worse simply because fewer leads have had time to close. A period's closed deals can also include leads acquired before that period.

### Good

```
The last 100 leads have 12 wins so far, while the previous 100 have 22. At 14 days
after acquisition, both cohorts had 12 wins. Compare them again when the new cohort
reaches the same age, or report the current cohort as still maturing.
```

Use the same elapsed time from lead creation to count wins, and include all leads eligible for that follow-up window. If lead creation or close dates are missing, report the observed counts and leave the cohort comparison unavailable.

---

## Gotcha: reporting CRM deal value as revenue

**Why it matters:** Weighted pipeline is a forecast. Presenting it next to real revenue, in the same format, makes it read as money in the bank.

### Bad

```
Revenue — USD 214,000
```

Where USD 86,000 is invoices and USD 128,000 is open pipeline.

### Good

```
Revenue — USD 86,400 (invoiced)
Pipeline — USD 128,000 open, weighted USD 41,000 (forecast, not booked)
```

Label the forecast every time. Owners plan hiring off these numbers.

---

## Gotcha: inventing attribution

**Why it matters:** When a campaign's revenue can't be traced, assigning it on a guess produces a return figure that looks authoritative and is fiction. Budgets move on these numbers.

### Bad

```
Paid social return: 3.4x
```

Derived by assuming every new customer that month came from paid social.

### Good

```
Paid social: USD 3,200 spend, 47 leads at USD 18 each. Revenue attribution unavailable —
the CRM isn't capturing source on closed deals. Cost per lead is solid; whether
those leads convert is the open question. Turning on source tracking would
answer it next month.
```

An honest gap with a fix is more useful than a confident fake number.

---

## Gotcha: the platform's numbers and the CRM's numbers disagree

**Why it matters:** The ad platform will claim 60 conversions while the CRM shows 41 leads. This is normal — different attribution windows, different definitions. Picking whichever is flattering misleads.

### Bad

Report 60, because it's the bigger number and it came from the ad platform.

### Good

```
The ad platform reports 60 conversions; the CRM received 41 leads with it as the source.
The 19-lead gap is normal attribution difference. Using the CRM number, since
that's what your team actually worked.
```

Report both, name the gap, and say which you used and why.

---

## Gotcha: one product carrying the entire trend

**Why it matters:** "Revenue up 12%" reads as broad health. If one SKU accounts for all of it and the other nine are flat or down, the business is more fragile than the headline suggests.

### Bad

```
Revenue up 12%. Growth engine is healthy.
```

### Good

```
Revenue up 12%, but entirely from one product — the summer bundle, up USD 9,800.
Every other product is flat or down. The headline is real; the breadth isn't.
```

Always check whether the trend survives removing the top mover.

---

## Gotcha: burying the funnel drop-off

**Why it matters:** The stage where the funnel loses the most is usually the highest-value finding available, and it is almost always cheaper to fix than any new campaign. It gets buried because it isn't a headline number.

### Bad

Lead with revenue and channel mix. Mention stage conversion in a bullet halfway down.

### Good

If one stage is losing more than 70% of what enters it, that is the headline sentence of the whole pulse, regardless of what revenue did.

---

## Gotcha: manufacturing three actions on a quiet month

**Why it matters:** If every pulse produces three urgent actions, the owner learns the actions are filler and stops reading them. The credibility of the recommendation is the asset.

### Bad

```
1. Consider testing a new ad channel.
2. Review your pricing.
3. Think about a referral program.
```

Generic, unprompted by any number in the pulse.

### Good

```
1. Nothing urgent this week. The engine is steady.
   The one thing worth watching: referral share has grown three months running
   with no effort behind it. Worth a deliberate test next month.
```

---

## Gotcha: marketing vocabulary the owner doesn't use

**Why it matters:** This audience is owner-operators, often the entire marketing department. Funnel-speak makes the pulse feel like it was written for someone else.

### Bad

```
Top-of-funnel velocity improved while MQL-to-SQL conversion degraded.
```

### Good

```
More new leads came in than last month, but fewer of them turned into real
opportunities.
```

Same finding. One of them gets acted on.
