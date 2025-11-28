# Calendar Sync — Rules

## Why This Matters
Calendar sync keeps your external calendar and MyScheduly aligned so you avoid double bookings and see your schedule where you work. Understanding the rules helps you connect correctly, switch providers safely, and keep times accurate.

## Core Rules
- One provider at a time
  - Connect Google or Microsoft, not both. Disconnect before switching.
- Initial full sync window
  - After connecting, a background sync aligns the last 7 days and the next 30 days so recent and upcoming plans match.
- Two‑way behavior
  - MyScheduly bookings appear in your external calendar when Confirmed.
  - External events appear in MyScheduly as blocked time to prevent overlaps.
- Live updates
  - After connection, changes flow automatically in near real time.
- Per‑user connection
  - Each staff member connects their own calendar; connections and events are scoped to the person.
 - Manual vs external items
   - Manual appointments in MyScheduly are the source of truth and are not overwritten by external edits. Events created from your connected provider can update corresponding synced items.

## Timezone Guidance
- Team timezone
  - Times use your team’s timezone for scheduling and reminders.
- Align calendars
  - Keep your external calendar’s timezone aligned with your team to avoid off‑by‑day surprises.
- Rescheduling
  - Changing time or staff for a Confirmed booking updates the external event in the correct timezone.
 - Consistent display
   - External events are converted to your team timezone so availability and reminders align across systems.

## Provider Switching
- Disconnect first
  - Stop syncing and remove the live‑update connection.
- Reconnect new provider
  - Start a new full sync with the other provider.
- Expect cleanup
  - Some provider‑specific items (like webhook subscriptions) are cleaned up when disconnecting to prevent leftovers.
 - Matching rule
   - Only events created by your current provider are updated or deleted. This prevents cross‑provider conflicts when switching.

## What Happens After Changes
- Confirming a booking: creates or updates events in your connected calendar.
- Canceling a booking: removes or updates events accordingly.
- Editing in MyScheduly: updates appear in your external calendar soon after.
- Editing externally: imported events block availability; avoid editing the same item in both systems at once.
 - Edge case protection: if a booking is cancelled while an event is being created, the external event is removed immediately to avoid duplicates.

## Best Practices
- Connect one provider per user; do not link both.
- Use the `Sync Now` action before busy days to align early.
- Make changes in MyScheduly and let sync update your external calendar to avoid conflicts.
- Keep timezone settings aligned across your team and external calendars.
 - Avoid simultaneous edits: pick one system (MyScheduly) for scheduling changes and let sync handle the rest.

## Why This Matters
Following these rules prevents duplicates, timing mistakes, and conflicting edits. A clean connection with aligned timezones keeps your day clear and predictable.
