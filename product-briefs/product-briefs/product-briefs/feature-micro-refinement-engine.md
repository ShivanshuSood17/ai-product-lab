# Feature Deep Dive: Micro-Refinement Engine

## Problem
Users rarely get their itinerary right on the first attempt. Small changes (weather, fatigue, preferences) force them to either:
1. Rebuild the entire itinerary manually, or  
2. Abandon structured planning altogether  

This creates friction in the most critical stage of the journey: **decision confidence before booking**.

## Why This Matters

- Planning is iterative, not one-shot
- Users want control without complexity
- Reducing friction here directly improves:
  - Booking conversion
  - User satisfaction
  - Retention for future trips

> Insight: The easier it is to tweak a plan, the more likely users are to trust and execute it.

## User Story

As a user, I want to modify one part of my itinerary without breaking the rest of the plan.

## UX Flow

1. User taps on a specific time block (e.g., Day 2 – Afternoon)
2. Clicks “Refine” or “Change this”
3. System asks intent:
   - “Too packed?”
   - “Different vibe?”
   - “Replace with similar activity?”
4. AI generates 3 alternatives:
   - Similar nearby option
   - Different category (e.g., indoor vs outdoor)
   - Low-effort alternative (rest/cafe)
5. User selects option
6. System:
   - Recalculates travel time
   - Adjusts adjacent slots if needed
   - Maintains overall trip integrity
  
## System Logic

- Each itinerary is broken into modular blocks (time + location + category)
- Refinement operates at block level, not full itinerary level
- Constraints:
  - Time availability
  - Distance radius
  - User preferences
  - Opening hours

Flow:
User action → Intent detection → Candidate generation → Constraint validation → Final options

## Edge Cases

- Suggested place is closed → fallback recommendations required
- Replacement creates time gap → auto-fill suggestions needed
- Multiple refinements create drift from original plan
- Poor internet → fallback to cached recommendations
  
## Metrics

- % of users using refinement feature (>40%)
- Avg refinements per itinerary (3–5)
- Itinerary completion rate (post-refinement)
- Drop-off rate before booking

## Trade-offs

| Decision | Option A | Option B | Choice |
|----------|----------|----------|--------|
| Refinement Depth | Full itinerary regen | Block-level changes | Block-level (faster, less disruption) |
| AI Creativity | High variation | Constraint-heavy | Constraint-heavy (travel reliability matters) |
| Speed vs Accuracy | Instant suggestions | Validated suggestions | Slight delay for validation |
