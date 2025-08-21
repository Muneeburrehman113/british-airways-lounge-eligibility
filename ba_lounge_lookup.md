### Sheet 1: Lounge Eligibility Lookup Table

| Flight Group        | Tier 1 % | Tier 2 % | Tier 3 % |
|--------------------|----------|----------|----------|
| Long-haul Morning    | 0.607    | 7.968    | 30.513   |
| Long-haul Lunchtime  | 0.638    | 8.067    | 30.732   |
| Long-haul Afternoon  | 0.601    | 7.898    | 30.235   |
| Long-haul Evening    | 0.602    | 7.929    | 30.333   |
| Short-haul Morning   | 0.619    | 7.920    | 30.330   |
| Short-haul Lunchtime | 0.638    | 8.067    | 30.732   |
| Short-haul Afternoon | 0.601    | 7.898    | 30.235   |
| Short-haul Evening   | 0.602    | 7.929    | 30.333   |

---

### Sheet 2: Justification

**1. How you chose to group the flights:**
- Flights are grouped by **Haul Type (Long/Short)** and **Time of Day (Morning, Lunchtime, Afternoon, Evening)**.
- These categories reflect operational differences in passenger distribution and flight patterns.

**2. Why your groupings make sense for this type of modeling:**
- Haul type impacts flight duration and lounge eligibility.
- Time of day affects peak lounge usage periods.
- Combining these groups allows estimation of lounge demand without exact flight or aircraft details.

**3. The assumptions you made and their reasoning:**
- **Tier 1:** Very few passengers (<1 per flight), representing high-status travelers.
- **Tier 2:** Moderate (~8 passengers per flight), consistent across times and regions.
- **Tier 3:** Majority (~30 passengers per flight), stable across flights.
- Assumed historical patterns will generalize to future schedules.

**4. How your model can scale to future or unknown schedules:**
- Percentages are applied per group rather than per flight.
- New flights can be categorized into these predefined groups, and the same percentages applied.
- Ensures flexible, reusable, and scalable lounge demand forecasting for BA Terminal 3.

