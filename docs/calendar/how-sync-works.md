---
title: How Sync Works
sidebar_position: 3
---

# How Sync Works

Understanding the logic behind the calendar sync helps you trust the system and work more efficiently. Here is exactly what happens when you connect your calendars.

## Two-Way Synchronization

The connection is a two-way street:

1.  **MyScheduly → Your Personal Calendar**
    *   When a client books an appointment, it appears on your personal calendar.
    *   If the appointment is rescheduled or cancelled in MyScheduly, your personal calendar updates automatically.

2.  **Your Personal Calendar → MyScheduly**
    *   If you have a personal event (like "Dentist Appointment" or "Lunch with Mom") on your Google/Outlook calendar, MyScheduly sees this time as "Busy."
    *   **Result:** Clients cannot book you during that time. You don't need to manually block off time in the app.

## Sync Timing

*   **Real-Time Updates:** In most cases, changes happen almost instantly. If you book a meeting in Outlook, that slot becomes unavailable in MyScheduly within seconds.
*   **Initial Sync:** When you first connect, we look at a specific window (past 7 days + next 30 days) to get everything up to date.

## Rules & Behaviors

### The "Source of Truth"
*   **MyScheduly Appointments:** Always edit these inside MyScheduly. If you try to change a client's appointment time by dragging it in your Google Calendar, it might *not* update the booking in the MyScheduly system correctly. Always use the MyScheduly dashboard for client bookings.
*   **Personal Events:** Edit these in your personal calendar. MyScheduly will simply read the new time and block it off.

### Privacy
*   **What Clients See:** Clients *never* see the details of your personal events. They simply see that time slot as "Unavailable" or "Booked." Your "Dentist Appointment" is private.

### Conflicts
*   If you have a personal event at 2:00 PM, MyScheduly will not allow a client to book you at 2:00 PM.
*   *Exception:* If you manually force a booking in MyScheduly (as an admin), you can override this block.

## What Gets Synced?
*   **Confirmed Bookings:** Yes.
*   **Pending Requests:** Usually no, until they are confirmed.
*   **Cancelled Bookings:** These are removed from your personal calendar to free up the space.
