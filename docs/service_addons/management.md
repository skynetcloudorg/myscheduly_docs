---
title: Management
sidebar_position: 2
---

# Service Add-ons — Management



Use this guide to attach/detach add-ons to services and manage their details.

## Create an Add-on
- Open Service Add-ons from your dashboard.
- Click “New Add-on”.
- Fill in details:
  - Name and Description.
  - Price and Cost (optional).
  - Duration (minutes, optional) if the extra adds time.
  - Active to show to clients.
- Link to services where this add-on is available.
- Click Save and confirm it appears for the selected services.

What happens after changes:
- Linked add-ons show only for those services in checkout.
- Deactivated add-ons disappear from booking until reactivated.

## Attach/Detach Add-ons
- Attach: Edit the add-on, select services, Save.
- Detach: Edit the add-on, remove services, Save.
- Deactivate: Turn off Active to hide temporarily.
- Delete: Remove if no longer needed.

## Roles and Permissions
- Staff cannot create, update, or delete add-ons; managers/owners manage add-ons (`app/Policies/ServiceAddOnPolicy.php:21–31, 34–43, 46–56`).

## Tips
- Use Active to control seasonal or promotional add-ons.
- Keep pricing simple and transparent.
- Always set Duration minutes if the extra adds time.

## Validation Checklist
- Confirm add-ons appear only for linked services.
- Verify totals and time update correctly when add-ons are selected.
- Test deactivation to ensure add-ons disappear from booking.
