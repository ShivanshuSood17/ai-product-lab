# 🗺️ Product Brief: WanderWeaver — AI Personalized Itinerary Builder

> **Version:** 1.0 | **Date:** April 2026 | **Author:** AI Product Lab
> **Domain:** B2C Travel Tech | **Stage:** Concept → MVP

---

## 1. Product Title

**WanderWeaver** — *No Two Trips Are Ever the Same*

---

## 2. Problem Statement

Planning travel is a massive time sink. Users spend countless hours across dozens of tabs (blogs, maps, review sites, booking portals) trying to piece together a cohesive trip that matches their specific interests, dietary needs, pace, and budget which wishing to explore the insta worthy travel destinations. Existing solutions are deeply flawed: pre-packaged tours are too rigid and generic, while DIY tools are overwhelming and offer zero guidance leaving the user clueless while planning and even when they reach the desired destination. Even the recommedations feel subpar if not properly planned as per the interests.

**The core pain points:**

| Pain | User Impact |
|---|---|
| Information Overload | Paralysis by analysis; settling for sub-optimal choices |
| Routing Nightmares | Realizing two planned activities are 2 hours apart, ruining a day |
| Generic Recommendations | Missing out on niche interests (e.g., best specialty coffee, specific art movements) |
| Friction in Refinement | Changing one plan cascades into manually re-doing the whole day |

> **Core insight:** Users want the expertise and ease of a luxury travel agent, but with the immediate control and personalization of DIY planning catering to their interests.

---

## 3. Target Persona

### Primary Persona: "The Time-Poor Professional" (30–45 yrs)
- **Profile:** High disposable income, low free time.
- **Goal:** Wants a highly curated, culturally rich experience without spending 20 hours planning it.
- **Frustration:** Hates researching logistics and reading through endless SEO-optimized travel blogs.

### Secondary Persona: "The Niche Explorer" (20–35 yrs)
- **Profile:** Passionate about specific interests (e.g., vegan street food, brutalist architecture, indie bookstores, bouldering).
- **Goal:** Wants an itinerary tailored entirely around their niche interests, rather than generic "Top 10 Tourist Traps".
- **Frustration:** Standard travel apps don't understand nuanced preferences.

---

## 4. User Journey

```
ONBOARDING → GENERATION → REFINEMENT → EXECUTION
```

### Step-by-Step Experience

**① Onboarding & Discovery (The Interview)**
- User engages in a dynamic, conversational interface (chat or voice).
- *AI:* "Where are we heading, and what's the vibe? Relaxing beach, intense cultural deep-dive, or something in between?"
- *User:* "Tokyo for 7 days. I want to focus on specialty coffee and deserts that are instagram recommended, obscure vintage synth shops, and I'm a vegetarian. Keep the pace relaxed."

**② Generation (The First Draft)**
- The AI constraint engine generates a complete, day-by-day itinerary.
- Crucially, it automatically clusters activities geographically to minimize transit time.

**③ Refinement (The Magic)**
- User reviews the visual itinerary.
- *User:* "Day 3 looks too packed, swap the museum for something outdoors."
- AI instantly recalculates Day 3, suggesting a nearby botanical garden, and adjusts the lunch reservation time without breaking the rest of the trip.

**④ Execution (The Trip)**
- The finalized itinerary is available in a clean mobile app.
- Features one-click export to Google Maps.
- Offline access ensures usability without roaming data.

---

## 5. Proposed Solution

**WanderWeaver** is an intelligent routing and recommendation engine disguised as a conversational AI. It combines the deep semantic understanding of LLMs (for parsing nuanced user desires) with rigorous constraint-solving algorithms and live POI (Point of Interest) APIs to guarantee physically realistic, optimized schedules.

**Core Architecture:**
- **Conversational Interface:** LLM-driven chat/voice intake.
- **Recommendation Engine:** Vector database mapping user intent to specific locations and activities.
- **Routing & Constraint Solver:** Google Maps API integration to ensure travel times are realistic and locations are clustered logically.

---

## 6. Key Features (Prioritized)

### 🔴 P0 — MVP Must-Haves
| Feature | Description |
|---|---|
| **Conversational Intake** | Chat interface to gather dates, budget, vibe, and specific constraints. |
| **Intelligent Itinerary Generation** | Outputting a logical, geographically clustered day-by-day plan. |
| **Micro-Refinements** | Ability to swap, delete, or regenerate specific blocks of time without resetting the whole plan. |
| **Maps Integration** | Exporting the final itinerary directly to Google Maps / Apple Maps. |

### 🟡 P1 — Growth Features (Month 3–6)
| Feature | Description |
|---|---|
| **Collaborative Planning** | Multiplayer mode: invite friends to vote on options or add constraints ("Sarah doesn't eat seafood"). |
| **Direct Booking Links** | Deep linking to Reserve with Google, OpenTable, and ticketing platforms. |
| **Dynamic Re-routing** | "It started raining" button -> instantly swaps outdoor activities for indoor ones nearby. |

### 🟢 P2 — Delight Features (Month 6–12)
| Feature | Description |
|---|---|
| **Budget Sync** | Estimating the daily cost of the itinerary based on user choices. |
| **AR Navigation** | Walking directions overlaid on the camera for complex local transit. |

---

## 7. Differentiation (vs. Competitors)

| Feature | WanderWeaver | ChatGPT (Base) | TripAdvisor | Expedia | MakeMyTrip | HostelWorld | Visit A City |
|---|---|---|---|---|
| Hyper-Personalization | ✅ High | ✅ High | ❌ Low | ❌ Low | ❌ Low | ❌ Low | ❌ Low |
| Realistic Routing/Logistics | ✅ High (API backed) | ❌ Low (Hallucinates) | ❌ Low | ❌ Low | ❌ Low |❌ Low |❌ Low |
| Easy Refinement of Parts | ✅ ❌ Low |❌ Low |High | 🟡 Medium (Requires prompting) | ❌ Low | ❌ Low |❌ Low |
| Collaborative Editing | ✅ Yes (P1) | ❌ No | ❌ No | ❌ No |❌ No |❌ No |❌ No |

**Unique moat:** We solve the "last mile" of AI travel planning. ChatGPT gives you a good list; WanderWeaver turns that list into a geographically accurate, time-bound, routable schedule that you can actually execute.

---

## 8. Monetization Strategy

### Revenue Streams

1. **Freemium Subscription (Primary)**
   - *Free:* Generate 2 itineraries per month, basic customization.
   - *Pro ($4.99/mo or $39.99/yr):* Unlimited itineraries, collaborative planning, dynamic weather re-routing, direct Maps export.
2. **Affiliate & Lead Generation (Secondary)**
   - Commission on hotel bookings, experiences (GetYourGuide/Viator), and restaurant reservations made through the app's deep links.

---

## 9. Success Metrics (KPIs)

### North Star Metric
> **Itineraries Executed** (Defined as an itinerary exported to Maps or opened within the destination geofence).

### Key Metrics
| Category | KPI | Target (Month 6) |
|---|---|---|
| **Activation** | Intake-to-Generation Rate | > 80% (Users who start the chat and get a full itinerary) |
| **Engagement** | Refinement Actions per Itinerary | 3–5 (Shows active curation, not just window shopping) |
| **Retention** | Multi-Trip User Rate | > 15% (Users who plan a second trip within 6 months) |
| **Retention** | Planning Time| < 30% (Reduced time to plan a trip) |
| **Monetization** | Free-to-Paid Conversion | > 4% |

---

## 10. Risks & Trade-offs

### 🔴 High-Risk

| Risk | Impact | Mitigation |
|---|---|---|
| **Hallucinations (Fake Places/Hours)** | Ruined trips, high churn | STRICT enforcement: LLM suggestions must be validated against a live Places API before being shown to the user. |
| **Unrealistic Transit Times** | Missed reservations, frustration | Use a hard constraint solver for routing; bake in 20% buffer time between activities. |

### ⚖️ Trade-offs

| Decision | Option A | Option B | Our Bet |
|---|---|---|---|
| **Interface** | Build custom map UI immediately | Rely on Google Maps export | **Maps Export (Faster time to market, familiar to users)** |
| **Booking** | Build native booking engine | Deep link to partners | **Deep links (Focus on our core competency: planning)** |
| **Data Source** | Scrape blogs/social media | Paid access to premium APIs | **Premium APIs (Reliability is paramount for travel)** |

---

*Generated by AI Product Lab · WanderWeaver Product Brief v1.0 · April 2026*
