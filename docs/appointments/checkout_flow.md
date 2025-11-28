# Checkout Flow & Sequential Scheduling

## Why This Matters
Checkout turns interest into confirmed bookings. When the flow is predictable, your pricing stays correct, multi‑service visits fit without conflicts, and clients get the right messages. Understanding each step helps you set policy, coach staff, and avoid surprises.

## How It Behaves
- Build the cart: clients add services and relevant add‑ons. Add‑ons increase both duration and price.
- Choose a date and time: only future times are offered online; the system validates choices in your team’s timezone.
- Sequential scheduling: the system finds back‑to‑back options that respect service durations, add‑ons, staff availability, Business Hours, and Buffer Time. If multiple valid chains exist, clients pick their preferred option.
- Voucher application: promo codes and gift cards validate immediately and show the discount. Discounts are spread proportionally across all items in the cart; gift cards deduct from their balance and keep any remainder for later. A single code applies per checkout, and the system protects against reusing the same code twice in one flow. If a code becomes invalid before final confirmation (for example, the balance is used elsewhere), checkout stops and asks the client to continue without the voucher or try a different code.
- Group creation: when the cart includes multiple services for the same visit, they are grouped so the client verifies once and confirms all together.
- Verification and confirmation: after checkout, the client receives a link to verify. Verified bookings move from Pending to Customer Confirmed. Teams can enable auto‑confirmation to move verified bookings to Confirmed automatically. Reminders send only when bookings are Confirmed.
- Status lifecycle: Pending → Customer Confirmed → Confirmed → Finished. Cancelled visits stop reminders and free the time on connected calendars.
- Conflict protection: overlapping times are prevented and Buffer Time is honored. Voucher processing includes safeguards to prevent double‑spending.

## What Happens After Changes
- Reschedule date, time, or staff: confirmed bookings update connected calendars; grouped bookings keep their sequence when possible, otherwise the system offers new valid options.
- Add or remove add‑ons: totals and durations recalculate; the analysis reruns to present valid slot choices.
- Apply or remove a voucher before completing checkout: totals update immediately; gift card balances reflect deductions once checkout completes.
- Cancel a booking: the client receives a cancellation message when email is enabled; calendars update for Confirmed bookings. Cancelling one visit in a group does not cancel the entire group.

## How To Use It
- Prepare services and add‑ons
  - Give each service a clear duration and price.
  - Attach add‑ons that correctly increase duration and price.
- Configure availability
  - Set Business Hours and Buffer Time in Organization Settings.
  - Turn on auto‑confirmation if you want verified bookings to become Confirmed automatically.
- Guide clients through checkout
  - Review cart items and add‑ons.
  - Select a future date and, if desired, a specific staff member.
  - Enter a voucher code when available; the discount should show immediately.
  - Complete checkout; the client looks for the verification message and confirms.
- Confirm and manage
  - Verification moves the group forward; with auto‑confirmation enabled, bookings become Confirmed without manual action.
  - Confirmed bookings receive reminders based on your notification settings.

## Example Scenarios
- Spa Day bundle
  - The client adds two services and one add‑on.
  - The system finds a back‑to‑back option that fits Business Hours and Buffer Time.
  - The client enters a gift card; part of the total is covered and the remainder stays on the card for next time.
  - After checkout, the client verifies; your team auto‑confirms the group. Calendars update and reminders are scheduled.
- Percentage discount across multiple items
  - The client applies a percentage promo code.
  - The system reduces the cart total and spreads the discount proportionally across all services and add‑ons.
  - If the code is removed before completing checkout, totals return to normal.

## Tips & Warnings
- Offer only future times for online scheduling; use past dates to record visits.
- Keep your team’s timezone accurate to avoid off‑by‑time issues.
- Enable auto‑confirmation only when your availability rules and verification process are solid.
- Prefer deactivating vouchers over deleting; this preserves history.
- Avoid editing the same booking in two systems at the same time; make changes in the app and let connected calendars update.

## Why This Matters
A reliable checkout ensures accurate scheduling, correct pricing, and smooth communications. With sequential scheduling, clients can book multi‑service visits in one pass while the system guards against conflicts and incorrectly applied discounts. This keeps your day predictable and your customers confident.
