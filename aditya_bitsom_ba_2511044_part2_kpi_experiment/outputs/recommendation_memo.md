# Executive Recommendation Memo
## Re: Campaign Experiment — Launch / No Launch Decision

**To:** Senior Leadership & Product Team  
**From:** Aditya Verma, Business Analyst | ID: bitsom_ba_2511044  
**Date:** 18 June 2026  
**Classification:** Internal — Confidential

---

## Executive Summary

We ran a controlled A/B experiment with **1,408 users** (693 Control, 715 Treatment) over a 30-day window to evaluate the impact of the new campaign treatment on user conversion and revenue outcomes.

**Bottom Line:** The Treatment campaign produced a **statistically significant** improvement in Paid Conversion Rate (3.17% → 6.99%, lift = +120.28%). All guardrail metrics passed their safety thresholds.

---

## Final Decision: 🚀 LAUNCH

---

## North Star Metric Performance

| Metric | Control | Treatment | Lift | Significant? |
|---|---|---|---|---|
| **Paid Conversion Rate** ⭐ | 3.17% | 6.99% | +120.28% | ✅ Yes (p=0.0006) |
| Avg Engagement Score | 57.02 | 62.93 | +10.36% | ✅ Yes |
| ARPU | ₹51.7493 | ₹53.8751 | +4.11% | ❌ No |
| Total Revenue (30d) | ₹35,862.28 | ₹38,520.71 | +7.41% | Directional |

---

## Supporting Metrics Summary

| Metric | Control | Treatment | Lift |
|---|---|---|---|
| Landing Page Visit Rate | 63.64% | 72.59% | +14.07% |
| Trial Start Rate | 25.11% | 29.09% | +15.86% |
| Onboarding Completion Rate | 15.58% | 21.26% | +36.41% |
| ARPPU | ₹1630.1036 | ₹770.4142 | -52.74% |
| Avg Days to Convert | 8.9d | 6.4d | -27.79% |

---

## Guardrail Analysis

All guardrail metrics were evaluated against pre-defined safety thresholds. A single breach would block launch.

| Guardrail | Control | Treatment | Threshold | Status |
|---|---|---|---|---|
| Refund Rate | 0.000 | 0.004 | ≤ 0.1 | ✅ PASS |
| Support Ticket Rate | 0.147 | 0.248 | ≤ 0.3 | ✅ PASS |
| Avg Days to Convert | 8.9 | 6.4 | ≤ 20 | ✅ PASS |

**Overall Guardrail Status: ✅ ALL PASSED**

---

## Segment Insights

- **Region with highest conversion lift:** North
- **Plan type with highest conversion:** Free users in Treatment group
- **Best-performing device:** Mobile

---

## Recommended Actions

### ✅ PROCEED WITH FULL LAUNCH

1. **Roll out to 100% of users** — The treatment passed all guardrails and shows statistically significant conversion improvement.
2. **Monitor post-launch KPIs** — Track Refund Rate and Support Ticket Rate weekly for the first 4 weeks post-launch to ensure guardrail compliance at scale.
3. **Segment-specific optimizations** — Prioritize rollout to the best-performing segments first (Premium plan users, Desktop users).
4. **ARPPU Watch** — Although ARPU improved, monitor ARPPU quarterly to ensure revenue per paying user remains healthy.
5. **Onboarding Deep-Dive** — Investigate onboarding completion rate improvement and replicate its success across other funnels.

---

## Limitations

- 30-day measurement window may undercount users with longer consideration periods.
- Experiment was run on a sample — results may differ at scale due to novelty effects.
- Missing device_type for 18 users — segment analysis may be slightly biased.
- No long-term retention data available — LTV impact is unquantified.

---
*Prepared by: Aditya Verma | BITSOM BA Capstone | bitsom_ba_2511044*
