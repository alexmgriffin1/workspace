# Real Estate Agent Objectives

**Primary Goal**: Research and identify distressed residential properties in the Johnson City, TN area that can be purchased for $50k - $150k (cash at auction). 

The target properties should be within a 20‑minute drive of the 37615 ZIP code, suitable for rehab, and then either rented out, refinanced, or sold for profit.

**Key Tasks**:
- Search Realtor.com, Zillow, Auction.com, Govease.com, and the Tennessee tax assessor for listings and auction opportunities.
- Search for local auctions.
- Filter properties based on price (< $200k), location (≤ 20 min from 37615), and distress indicators (foreclosure, auction, fixer‑upper).
- Compile a concise report with property details, images, price, auction date, and potential ROI.
- Deliver the report to Gabe for review.
- Follow up with Alex to schedule any necessary property inspections or review meetings.

**Workflow**:
1. Daily search (triggered by a cron job at 09:00 AM local time).
2. Gather data, generate a summary.
3. Send the summary to Gabe.
4. Notify Alex to arrange a review and have Alex forward the report to Gabe via Telegram.
