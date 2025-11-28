---
title: Calendar Integration — Overview
sidebar_position: 1
---

# Calendar Integration — Overview

Last updated: 2025-11-27

## Purpose and Audience
The calendar integration connects MyScheduly to your external calendar so your appointments and events stay in sync. It is designed for:
- Managers/Owners: keep team schedules aligned and avoid double bookings.
- Staff: see bookings in your personal calendar and receive updates in real time.

## How It Behaves
When you connect a provider, MyScheduly starts a full synchronization in the background. This makes both calendars match without you needing to edit the same event twice.
- Initial full sync: covers the last week and the next month (37 days total) so recent and upcoming plans stay aligned.
- Two‑way updates: your external events appear in MyScheduly, and your bookings in MyScheduly appear in your external calendar.
- Sync duration: usually 1–5 minutes depending on how many events you have. You can keep using the app while it runs.
- One provider at a time: you can connect either Google or Microsoft. To switch, disconnect the current one first.
- Real‑time updates: after connecting, changes are reflected automatically so both calendars stay in step.
- Clear status: the page shows whether you’re connected, which account is linked, and when it was last updated.

When you disconnect:
- MyScheduly stops syncing, and live updates turn off.
- Previously synced appointments remain in MyScheduly.
- Any blocking times created to protect your schedule may be removed from your external calendar to prevent leftovers.

## How To Use It
- Open Calendar Integration.
- Choose Google or Microsoft and click Connect. Follow the steps and return to MyScheduly.
- After connecting, you’ll see a success message and a full sync will start automatically.
- Use Connected Actions to:
  - Sync Now: manually refresh your calendars if you expect a busy day.
  - Disconnect: stop syncing and prepare to switch providers.
  - Advanced options: test live updates or refresh the live‑update connection if needed.

## Example Scenario
You connect Google Calendar on Monday morning.
- The page confirms the connection and starts a full sync. In a few minutes, your last week’s events and the next month’s appointments line up.
- You see “Connected” with your Google email, and a status area confirms live updates are active.
- A client reschedules an appointment in MyScheduly. Your Google Calendar updates automatically because live updates are on.
- Later, you disconnect to switch to Microsoft Calendar. The system removes webhooks and stops syncing. You then connect Microsoft and the same initial full sync begins.

## Best Practices
- Keep one provider connected. This reduces conflicts and makes updates predictable.
- If you run campaigns or expect heavy booking days, use `Sync Now` to align early.
- Avoid editing the same event in both calendars at once. Make changes in MyScheduly; they will appear in your external calendar.
- Expect daily activity to be fast, with occasional rate limits during large syncs.
- If updates seem delayed, check the status area. Use Advanced options to test or refresh live updates.

## What Happens After Changes
- Connecting a provider:
  - Starts a background full sync and enables real‑time updates. The dashboard and your external calendar gradually converge as events are processed.
- Disconnecting a provider:
  - Stops syncing and turns off live updates. Your external calendar will no longer receive changes until you reconnect.
- Refreshing live updates:
  - Restores real‑time syncing. You’ll see confirmation in the status area.

## Troubleshooting Tips
- “Not Connected” status: click Connect and complete authorization. If another provider is connected, disconnect it first.
- Live updates not appearing: use the Advanced options to test or refresh the live‑update connection.
- Slow or partial syncs: wait 1–5 minutes for the initial pass. Large calendars take longer. Use Sync Now if needed.
- Heavy activity days: expect some throttling to keep your account safe. Try again after a short pause.

## Helpful Notes
- If you change your connected account (for example, switching from Google to Microsoft), disconnect first, then connect the new one.
- Keep your personal calendar time zone aligned with your team’s time zone in MyScheduly to avoid off‑by‑one‑day confusion.

## Related Guides
- Sync Rules: [Read more](sync_rules.md)
- Troubleshooting: [Read more](troubleshooting.md)

## Why This Matters
Keeping your calendar connected prevents double bookings, supports real‑time updates for changes, and avoids manual entry in two systems. When you adjust connections or webhook settings, MyScheduly reacts immediately — either syncing more often, or pausing updates — so your daily workflow stays clear and consistent.
