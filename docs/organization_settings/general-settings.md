---
title: General & Booking Rules
sidebar_position: 2
---

# General & Booking Rules

These fundamental settings determine how your booking engine operates. Setting these correctly ensures that appointments land in the right time slot and are paid for in the correct currency.

## Basic Configuration

### Timezone
This is the most critical setting for your schedule.
*   **What it does:** All appointments, reminders, and staff schedules are calculated based on this timezone.
*   **Why it matters:** If you are in New York but set to London time, your 9 AM client will show up when you are at lunch.
*   **Changing it:** If you move, update this setting. Future appointments will shift to display the correct local time in the new zone.

### Currency
*   **What it does:** Sets the symbol (e.g., $, £, €) displayed next to your prices.
*   **Note:** This is for display and payment processing. Ensure your connected payment gateway (like Stripe) supports this currency.

## Booking Rules

These rules control the flow of incoming appointments.

### Auto-Confirm
*   **ON (Recommended for most):** When a client books a slot, it is immediately marked as `Confirmed`.
    *   *Benefit:* Less admin work for you; instant certainty for the client.
*   **OFF:** Bookings arrive as `Pending`. You must manually approve each one.
    *   *Benefit:* Gives you total control if you need to screen clients or check resources manually.

### Buffer Time
*   **What it is:** A mandatory gap between appointments.
*   **Example:** If you set a 15-minute buffer, and an appointment ends at 10:00 AM, the next bookable slot won't start until 10:15 AM.
*   **Why use it:** Use this time to clean your station, take a break, or catch up on notes.

## Business Hours
This defines your "Open" sign.
*   **How it works:** Clients can only book slots that fall within these hours.
*   **Days Off:** Leave the start/end times blank to mark a day as "Closed".
*   **Holidays:** You can block specific dates (like Christmas or National Holidays) in the **Holidays** tab to override your standard weekly hours.
