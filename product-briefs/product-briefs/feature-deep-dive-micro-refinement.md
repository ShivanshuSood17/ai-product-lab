# Feature Deep Dive: Micro-Refinement Engine

## Problem

Users don’t want to regenerate entire itineraries for small changes.

## User Story

As a user, I want to modify one part of my itinerary without breaking the rest of the plan.

## UX Flow

1. User selects a block (e.g., Day 2 Afternoon)
2. Clicks “Regenerate”
3. AI suggests 3 alternatives
4. User selects one → system updates dependencies

## Edge Cases

* Time overlaps
* Location conflicts
* Closed venues

## Metrics

* % users using refinement
* Avg refinements per itinerary

## Trade-offs

* Speed vs accuracy
* AI creativity vs constraint logic
