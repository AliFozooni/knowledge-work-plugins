# Thresholds

Status cutoffs for each view. These are SMB defaults — they should be tuned to the owner's actual targets.

Any threshold still marked "confirm with owner" should produce a one-line note at the top of the first pulse so the owner knows to correct it.

---

## Channel trend

**Revenue versus prior period**
- Green: flat or growing
- Yellow: down 0% to 10%
- Red: down more than 10%

**Revenue versus same period last year**
- Green: up 10% or more
- Yellow: down 5% to up 10%
- Red: down more than 5%

**Channel concentration**
- Green: no single channel above 60% of revenue
- Yellow: one channel at 60% to 80%
- Red: one channel above 80% — this is a fragility flag even when the trend is up

---

## Funnel conversion

**Lead volume versus prior period**
- Green: flat or growing
- Yellow: down 0% to 20%
- Red: down more than 20%

**Win rate**
- Green: 20% or higher — confirm with owner, this varies enormously by industry
- Yellow: 10% to 20%
- Red: below 10%

**Stage drop-off**
- Green: no single stage loses more than 50% of what enters it
- Yellow: one stage loses 50% to 70%
- Red: one stage loses more than 70% — this is almost always the highest-value finding in the pulse

**Response speed**
- Green: median first response under 1 hour
- Yellow: 1 to 24 hours
- Red: over 24 hours

Response speed deserves attention out of proportion to its size. Inbound leads go cold fast, and it is the cheapest thing on this list to fix.

---

## Campaign return

**Return on ad spend**
- Green: 3x or better
- Yellow: 1.5x to 3x
- Red: below 1.5x

**Cost per lead, trend**
- Green: flat or falling
- Yellow: rising 0% to 25%
- Red: rising more than 25%

Apply the color to the observed cost change. Before recommending a budget change:

1. Compare equal-length periods with the same lead definition, attribution window, currency, and spend coverage. Show spend and lead counts alongside each cost per lead. If either period has zero leads, show spend and zero leads, and mark cost per lead unavailable.
2. If segment-level spend and leads are available, compare cost per lead within the same campaigns, audiences, or geographies. Aggregate cost per lead is total spend divided by total leads. It can rise solely because a larger share of leads came from higher-cost segments. Call out new or missing segments separately and show how much of the total the matched segments cover.
3. If comparable segments became more expensive, report the decline and investigate likely drivers such as auction cost, creative fatigue, conversion, or tracking. If only the mix changed, report that shift and compare qualified lead cost or realized return where attribution and follow-up windows are comparable. If the exports lack the detail, state what is missing and request it before recommending a change based on this signal.

Treat saturation as a hypothesis. Describe the observed spend and lead changes separately. Two before-and-after totals cannot establish how many leads the extra spend caused or what would happen if it were removed. With cost-per-lead data alone, say the budget decision is undetermined and recommend gathering the missing evidence. Leave out numeric spend targets, including a rollback to the previous spend. A budget test with a credible concurrent comparison can help separate the spend effect from changes in the market.

---

## Product performance

**Top and bottom**
- Always name the top 3 and bottom 3 by revenue
- Flag any product whose revenue moved more than 25% either direction

**Concentration**
- Green: top product under 30% of revenue
- Yellow: 30% to 50%
- Red: above 50% — name it, because the whole trend is really that one product

---

## Customer sentiment

**Average review score, trailing 90 days**
- Green: 4.3 or higher
- Yellow: 3.8 to 4.3
- Red: below 3.8

**Review score trend**
- Green: flat or improving
- Yellow: down up to 0.3
- Red: down more than 0.3

**Disputes and chargebacks**
- Green: under 0.5% of transactions
- Yellow: 0.5% to 1%
- Red: above 1%

**Repeat purchase rate**
- Green: flat or improving
- Red: down more than 10% versus prior period

---

## A note on applying these

Thresholds set the status color. They do not write the finding.

"Win rate is yellow" is not useful. "Win rate fell to 14% from 22%, and the drop is entirely in leads from the trade show list" is. Use the cutoffs to decide what deserves attention, then go look at why.
