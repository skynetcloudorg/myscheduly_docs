---
title: Client Redemption Process
sidebar_position: 4
---

# Client Redemption Process

Understanding how your customers experience vouchers helps you troubleshoot issues and design better promotions. This guide explains what happens when a client attempts to use a code at checkout.

## How Clients Apply Codes

During the booking checkout process, your clients will see an option to "Add a voucher or gift card." They simply enter the code you provided and click apply.

The system immediately checks the code validity. If valid, the discount is applied to the total. If invalid (expired, limit reached, or typo), they will see a clear error message.

## Validation Logic

When a code is entered, the system runs several checks in the background to ensure it is allowed:

1.  **Is it Active?** The code must be marked as active in your settings.
2.  **Is it Expired?** Today's date must be on or before the expiration date.
3.  **Are Limits Reached?** The system checks if the global usage limit or the per-user limit has been hit.
4.  **Is the Cart Eligible?** The total value of the services in the cart must meet the "Minimum Order Value" if you set one.

**Double-Spending Protection:** The system prevents the same code from being applied simultaneously from multiple devices or sessions to ensure a unique code isn't used more than allowed.

## How Discounts Are Calculated

### Fixed and Percentage Discounts
When a discount is applied, it reduces the total amount due.
*   If a client has multiple items in their cart, the discount is often **distributed proportionally** across the items. This is important for refunds—if a client cancels one service from a package, the refund will reflect the discounted price of that specific service, not the full price.
*   Percentage discounts are capped at 100% (free), so the total can never go below zero.

### Gift Card Redemption
Gift cards work like a wallet.
*   **Partial Use:** If the order total is *less* than the gift card balance, the system only deducts what is needed. The remaining balance stays on the card for future use.
*   **Split Payment:** If the order total is *more* than the gift card balance, the entire gift card is used, and the client pays the remaining difference with another payment method (like a credit card).

## What the Client Sees
*   **Success:** The total price updates immediately, showing the original price crossed out or the deduction listed as a line item.
*   **Gift Cards:** They see how much balance was used and how much (if any) remains.
