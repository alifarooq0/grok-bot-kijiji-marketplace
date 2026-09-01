---
name: kijiji-search-listings
description: Search Kijiji for listings by keyword, category, location, and price. Use when the user wants to find items for sale on Kijiji.
---

# Search Kijiji listings

## Goal

Find relevant Kijiji listings and summarize options the user can act on.

## Steps

1. Confirm what they want (item, budget, condition, location or radius).
2. Prefer a direct Kijiji search URL with query params when possible for their city or metro.
3. Open Kijiji in the browser (signed-in session if available) and search with:
   - Keyword / category
   - Location and distance
   - Price min/max
   - Condition or type filters when useful
4. Collect a shortlist (about 5–10): title, price, location, posted time, link, and one-line note (deal / fair / overpriced / red flag).
5. Flag common issues: vague photos, no meetup area, price far off comps, pressure tactics in the ad.

## Output

- Shortlist table or bullets with links
- Best pick + why
- Gaps (need a different city, more budget, wait for new posts)
