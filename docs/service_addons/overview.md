---
title: Overview
sidebar_position: 1
---

# Service Add-ons



## Why This Matters
Add-ons let customers customize their appointments and increase average order value. Correct linking ensures only relevant extras show, and accurate duration/price keep schedules and billing right.

## When You Use It
- Offer enhancements that complement a base service.
- Add time and price when customers select an extra.
- Control which services each add-on applies to.

## How Add-ons Behave
- Each add-on has Name, Description, Price, Cost (optional), and Duration (optional minutes).
- Add-ons must be linked to services; only linked add-ons appear in checkout (`resources/views/checkout/cart.blade.php:126–136`).
- Selected add-ons add to appointment totals and time (`app/Models/Appointment.php:165–175, 180–189`).
- Inactive add-ons are hidden from customers.

## How to Use
- Open Service Add-ons from your dashboard.
- Click “New Add-on”, enter details, link to applicable services, and set to Active.
- Edit later to attach/detach services or deactivate temporarily.

## Practical Tips
- Keep descriptions short and benefit-focused.
- Set Duration minutes whenever the extra adds time.
- Link add-ons selectively to avoid clutter.
- Deactivate seasonal add-ons when not offered.
