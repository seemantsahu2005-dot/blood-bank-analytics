# Blood Bank Analytics Dashboard

I built this project because everyone around me was making sales dashboards 
and HR dashboards. I wanted to build something that actually matters.

Blood banks in India run on guesswork. Nobody tracks which blood type is 
running out, which hospitals are still waiting, or which units are about to 
expire. I decided to fix that — at least on paper.

## What I Used
- MySQL — to store and query the data
- Power BI — to visualize everything

## The Database
5 tables — donors, camps, donations, blood_requests, blood_inventory.
All based on real hospitals and locations from the MP region.

## Questions I Tried to Answer
- Which blood type gets donated the most?
- Are donations going up or down month by month?
- Which donation camp brought in the most blood?
- Which blood types are critically short right now?
- Which hospitals keep running out?
- Which units are about to expire and get wasted?

## The Dashboard
4 pages in Power BI:
- Inventory Overview — how much blood do we actually have
- Donation Trends — are things getting better or worse
- Hospital Demand — who needs what and are we delivering
- Shortage Alerts — the page that matters most, color coded red yellow green

## What I Found
- O-, B-, and AB- are critically low — under 5 units each
- Only 40% of hospital requests are being fulfilled
- Rotary Club camps consistently outperform everyone else
- AB- expires first and needs to be dispatched immediately

## Connect
**Seemant Sahu** — Data Analyst  
[LinkedIn](https://linkedin.com/in/seemant-sahu-da) | [GitHub](https://github.com/seemantsahu2005-dot)
