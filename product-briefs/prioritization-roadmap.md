# 📊 Prioritization & Roadmap — WanderWeaver

## Assumptions

- Early users = high-intent international travelers (premium segment)
- Avg user plans 2–3 trips/year
- Planning time currently ~8–10 hours per trip
- Users drop off if value not seen within first 2 minutes## 🎯 Goal

Identify which features to build first for MVP vs future iterations using RICE framework.

---

## 🧮 RICE Framework

RICE = Reach × Impact × Confidence / Effort

| Feature                 | Reach | Impact | Confidence | Effort | Score |
| ----------------------- | ----- | ------ | ---------- | ------ | ----- |
| Conversational Intake   | 8     | 9      | 8          | 6      | 96    |
| Itinerary Generation    | 9     | 10     | 7          | 8      | 78.75 |
| Micro-Refinement Engine | 7     | 9      | 7          | 7      | 63    |
| Maps Export             | 8     | 7      | 9          | 5      | 100.8 |
| Collaborative Planning  | 6     | 6      | 6          | 8      | 27    |
| Dynamic Re-routing      | 5     | 7      | 6          | 9      | 23.3  |

## RICE Scoring Logic

- Reach: % of users impacted in early stage
- Impact: Effect on core metric (trip planning completion)
- Confidence: Based on known user behavior patterns
- Effort: Relative engineering complexity (1–10 scale)---

## 🧠 Key Takeaways

* Maps Export scores highest due to low effort + high utility
* Itinerary Generation is critical despite higher effort
* Micro-refinement is a strong differentiator but not Day 1 requirement

---

## 🚀 MVP Strategy (Phase 1)

Focus: Prove core value proposition

Build:
- Conversational Intake → Capture user intent quickly
- Itinerary Generation → Deliver immediate value
- Maps Export → Enable real-world usability

Why this works:
- Users see value within first interaction
- Low friction → high activation
- Avoids overbuilding before validation

> Goal: Answer one question — “Will users trust AI to plan their trips?”

## ❌ What We Are NOT Building (Yet)

- Collaborative Planning → Requires network effects
- Dynamic Re-routing → High complexity, depends on real-time data
- AR Navigation → Low impact vs effort

Reason:
Focus on solving planning first, not execution complexity

---

## 📈 Phase 2 (Enhancement)

Build:

* Micro-Refinement Engine
* Basic personalization improvements

Goal: Improve engagement + usability

---

## 🌟 Phase 3 (Growth & Differentiation)

Build:

* Collaborative Planning
* Dynamic Re-routing

Goal: Increase retention + network effects

---

## 💡 Key Product Insight

Users don’t need a perfect itinerary.

They need a **good starting point that is easy to refine**.

Winning = reducing effort, not maximizing intelligence.
