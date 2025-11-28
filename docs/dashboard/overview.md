---
title: Dashboard — Overview
sidebar_position: 1
---

# Dashboard Overview

Version: 1.0.28 | Last updated: 2025-11-27

## Purpose and Audience
The dashboard gives a live snapshot of business performance. It is designed for:
- Managers/Owners: financial metrics, service performance, customer satisfaction.
- Staff: a focused view of today’s schedule and personal performance.

## How to Use
1) Select a period in the Filters bar (e.g., Today, Last 30 Days).
2) Optionally filter by Service or Staff.
3) Click Refresh to fetch updated analytics.
4) Read metric cards for quick status, then review charts and tables for trends and details.

## Screenshots
- Dashboard overview: ![Dashboard Overview](images/dashboard_overview.svg)
- Layout map: ![Layout Components](images/dashboard_layout.svg)

## Tips & Tricks
- Use “Last 30 Days” to see trend lines with daily points.
- Compare service performance using market share and growth indicators.
- If you use gift cards, remember gift card revenue is tracked when sold, not when redeemed.

## Navigate to Details
- Indicator explanations: [Dashboard — Indicators](indicators.md)
- Help and fixes: [Dashboard — Troubleshooting](troubleshooting.md)

## Validation Checklist
- Filters apply correctly and reflect in all components.
- Revenue and AOV numbers match your appointments and gift card sales.
- Service performance chart labels match your configured services.

## How It Behaves
- When you adjust filters, the dashboard updates all cards, charts, and tables together after you click Refresh. A few behaviors help keep the view readable and accurate:
- Date range formatting: short ranges (up to 31 days) show daily points; longer ranges (like This Year) show monthly points. This keeps the chart clear without losing the trend. 
- Comparison labels: each period shows a clear “previous period” label (for example, “Previous 30 Days (31–60 days ago)” when you select Last 30 Days) so you know what the chart is comparing against. 
- Team timezone: “Today”, weekly ranges, and all timestamps follow your team’s timezone. If you update the timezone in General Settings, “Today” and reminders shift to your local time automatically. 
- Staff vs Manager views: staff accounts are redirected to a focused staff dashboard; owners/managers see the full dashboard.
- Revenue trend composition: appointment revenue is always included; gift card sales may be included when available for the selected period to reflect total inflows.
- Financial visibility: some financial cards and analytics appear only for users with the appropriate permission. Staff may see a simplified view without financial totals.

## Example Scenario
You run a “Weekend Wellness” promo.
- Select Last 30 Days and click Refresh. You’ll see daily points in Revenue Trends with a comparison label “Previous 30 Days”.
- Filter by the Massage service to isolate impact. The trend line rises across the promo days.
- Open Voucher Analytics to check ROI and cost savings. If ROI shows 35% and usage is steady, consider repeating the offer.


## Best Practices
- Always confirm the date range before comparing numbers.
- Expect monthly points when using long ranges (like This Year); this is normal.
- Keep your team timezone accurate to avoid off‑by‑one‑day reading.
- When gift cards are part of your business, remember: gift card revenue is counted at sale, and may also appear in trends to reflect cash inflow.
