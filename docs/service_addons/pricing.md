---
title: Pricing
sidebar_position: 3
---

# Service Add-ons — Pricing



## Cost Structure and Billing
- Add-on Price adds to the base service price when selected.
- Duration minutes extend the appointment length when selected.
- Cost (optional) feeds margin/profitability reporting; customers do not see cost.
- Only Active add-ons appear to customers.

## Example Calculation
- Base Service: Haircut — Price: $50, Duration: 45 minutes.
- Add-on: Deep Conditioning — Price: $15, Duration: +15 minutes.
- Client selects both.
- Total Price: $50 + $15 = $65.
- Total Duration: 45 + 15 = 60 minutes.

## Backend Behavior (Verified)
- Totals add all selected add-on prices to the service price (`app/Models/Appointment.php:165–175`).
- Duration adds selected add-on minutes to the service duration (`app/Models/Appointment.php:180–189`).
- Availability uses total duration (service + add‑ons) when searching slots (`app/Services/AppointmentAvailabilityService.php:110–133, 142–174, 219`).

## Tips
- Keep add-on prices transparent; avoid hidden fees.
- Use cost tracking to adjust pricing based on margin goals.
- Ensure duration changes reflect reality to prevent conflicts.

## Validation Checklist
- Book a service with and without add-ons; verify totals and time.
- Confirm reports show margins correctly when Cost is filled.
- Check deactivated add-ons do not appear or affect totals.
