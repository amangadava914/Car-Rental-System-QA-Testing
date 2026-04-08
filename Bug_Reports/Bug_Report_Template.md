## Bug Report

**Bug ID:** `BUG-101`
**Title:** Discount not applied on booking confirmation page after valid promo code entry.
**Module:** Booking Module
**Severity:** High
**Priority:** High
**Environment:** Test (https://carrental-test.com), Chrome v123, Windows 11

**Description:**
After entering a valid promo code 'SAVE10' on the booking form, the price breakdown on the confirmation page does not show the discount, and the final payable amount remains unchanged. The user is charged the full amount.

**Pre-conditions:**
1. User is logged in.
2. A car is selected and available for the chosen dates.

**Steps to Reproduce:**
1. Select a car and proceed to the booking form.
2. In the 'Promo Code' field, enter the valid code 'SAVE10'.
3. Click 'Apply'.
4. Observe the 'Price Summary' section.
5. Click 'Confirm Booking'.

**Actual Result:**
The discount is not applied. The 'Total Amount' remains the original price.

**Expected Result:**
A 10% discount should be applied, and the 'Total Amount' should be updated to reflect the discounted price.

**Attachments:**
[Link to screenshot of price summary before and after applying code]

**Reported By:** Aman Gadava
**Date:** 2025-06-08