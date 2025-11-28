---
title: Permissions Matrix
sidebar_position: 5
---

# Permissions Matrix

Assigning the right role is crucial for security. Use this matrix to decide which role fits each staff member.

## Role Definitions

### 👑 Owner
*   **Who:** The business owner.
*   **Power:** Unlimited.
*   **Key Abilities:** Manage billing, delete the team, edit public website, view all financial reports.

### 🛡️ Manager
*   **Who:** Receptionists, shift supervisors, or office managers.
*   **Power:** High operational control, but no "destructive" power.
*   **Key Abilities:** Manage everyone's appointments, edit customer profiles, update service prices, view team schedule.
*   **Restrictions:** Cannot delete the team, change the subscription, or edit the public website design.

### 👤 Staff
*   **Who:** Service providers (stylists, barbers, therapists).
*   **Power:** Focused on their own work.
*   **Key Abilities:** View/Manage *their own* schedule and appointments.
*   **Restrictions:** Cannot see other staff's schedules, cannot see total business revenue, cannot change settings.

## Feature Access Table

| Feature | Owner | Manager | Staff |
| :--- | :---: | :---: | :---: |
| **Team Settings** | | | |
| Manage Subscription | ✅ | ❌ | ❌ |
| Invite/Remove Members | ✅ | ❌ | ❌ |
| Change Team URL | ✅ | ❌ | ❌ |
| **Operations** | | | |
| View All Appointments | ✅ | ✅ | ❌ (Own only) |
| Edit Services & Prices | ✅ | ✅ | ❌ |
| Edit Public Website | ✅ | ❌ | ❌ |
| **Data & Finance** | | | |
| View Total Revenue | ✅ | ✅ | ❌ |
| View Customer List | ✅ | ✅ | ✅ |

## Best Practices

1.  **Limit Owners:** Try to have only 1 or 2 Owners. This prevents accidental changes to billing or critical settings.
2.  **Protect Privacy:** Staff roles are designed to hide sensitive financial data. If a staff member doesn't need to see the shop's total monthly revenue, keep them as "Staff".
3.  **Receptionists:** The "Manager" role is perfect for front-desk staff who need to book appointments for everyone but shouldn't be able to delete the website.
