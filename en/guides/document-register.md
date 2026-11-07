---
title: "The document register for your accountant"
description: "The “Document register” page in the menu: the month's documents by issue date, with MARK, myDATA type and status; “Month” and “Export CSV” for your accountant, with the columns “Date source”, “Currency” and “Corrects month”; the kinds of document, the columns and the statuses “Issued”, “Voided” and “Connection removed”; why the register goes by issue date and not by the “Revenue basis” setting; what the flags “Possibly issued late”, “Cancellation fee at 13% VAT, as for the stay — to be checked”, “Estimated date” and “No issue date” mean; credit notes from Elorus and the buttons “Update credit notes”, “Link to original”, “Change link”, “Add credit note” and “Remove entry”; which role does what, and “Close month”."
---

# The document register for your accountant

The **Document register** gathers each month's documents the way your accountant needs them: every document on its own line, by issue date. You'll find it in the menu, below **Resilience Fee**.

## Month and export

- Under **Month**, choose the month you want to see.
- **Export CSV** downloads the same table for your accountant. The file also has the columns **Date source**, **Currency** and **Corrects month**.

## What each line shows

The **Kind** column says what the document is:

| Kind | What it is |
|------|------------|
| **Accommodation document** | The receipt or invoice for the stay |
| **Payment receipt** | The receipt for the payment of the stay |
| **Climate fee receipt** | The Climate Resilience Fee receipt |
| **Cancellation fee** | The document for the amount you kept from a cancelled booking |
| **Credit note** | A credit note you issued in Elorus |

**Status** says whether the document was **Issued** or **Voided**. **Connection removed** means the connection of the invoicing organization that issued it was removed.

The other columns show the **Issue date**, **Number**, **Total**, **Net amount**, **MARK** (the unique number myDATA registered the document under), **myDATA type**, **Booking** and **Counterparty VAT number** (on an invoice to a business).

## Why the register goes by issue date

For your accountant, every document belongs to the month it was issued in, so the register always goes by issue date. The [**Revenue basis**](/en/guides/revenue-basis) setting decides which month booking revenue counts in on DeskBoy's revenue reports, and the register doesn't follow it. So a stay can count in July on the revenue reports while its document sits in August's register, because it was issued in August.

## The flags

The **Flags** column shows anything worth a second look, and most flags say themselves what to check. Three need a little more explanation:

- **Possibly issued late**: the stay's document is dated after the issuing deadline, that is, a receipt after the check-out day or an invoice to a business after the 15th of the following month. DeskBoy only flags it; show it to your accountant.
- **Cancellation fee at 13% VAT, as for the stay — to be checked**: the cancellation fee is issued at the stay's VAT rate. The flag is on every cancellation fee, so your accountant can confirm the rate.
- **Estimated date**: this document's issue date wasn't read from your invoicing provider, so the register shows an estimate: the day DeskBoy recorded the issue (in the CSV, **Date source**: **Estimate**). **No issue date** means there isn't even an estimate. Either way, check the document's date at your invoicing provider.

## Credit notes

Credit notes you issue in Elorus for your bookings go into the register for the month they were issued, like any other document.

- **Update credit notes**: if a month's credit notes haven't been fully updated from your invoicing provider, a notice with this button appears above the table. The button starts a new read of the credit notes from the provider, which runs in the background: check the register again later, and the notice will be gone once it's complete.
- **Link to original**: appears in the **Flags** column of a credit note, next to the flag **Not linked to an original document** or **The provider lists more than one original document: check which one applies**. Type the **Document number**, choose the right document and press **Link**.
- **Change link**: changes the document you linked a credit note to. If your invoicing provider shows the original later, the provider's link replaces yours and is recorded in the **Activity history**.
- **Add credit note**: for a credit note issued by an invoicing organization whose connection was removed. Credit notes from such an organization can no longer be read from the provider, so you record them yourself: fill in the credit note's details, choose the **Original document** and press **Add**. The button appears above the table when such an organization exists.
- **Remove entry**: removes a credit note you recorded with **Add credit note**, from its line in an open month. A credit note dated in a closed month shows as a correction in the next open month, and you remove it from there.

## Who does what

Every role, the Accountant included, can see the register and use **Export CSV**. **Update credit notes**, **Link to original**, **Change link**, **Add credit note** and **Remove entry** are for the Owner and the Admin. So is **Close month**, on the Agency plan: see [Closing a month](/en/guides/month-close).
