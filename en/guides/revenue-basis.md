---
title: "Revenue basis"
description: "The “Revenue basis” setting under Settings → Advanced, for the Owner and the Admin: which month each booking's revenue counts in, in the revenue figures from Nio, AI tools and the Data Access API, and on owner statements; that it does not affect documents, VAT, myDATA or the document register; the three options “Check-out date”, “Document issue date” and “Per night” with the same example; cancellation fees; how you change the setting (“Change the revenue basis?”) and when the change applies, the “Starts” and “In effect today” badges, “Cancel change”, “Change history”, an owner statement on two bases; a stay across New Year and your accounting books."
---

# Revenue basis

Which month does a stay from 28 July to 2 August count in, on DeskBoy's revenue reports? The **Revenue basis** setting decides this for the whole account. You'll find it under **Settings → Advanced**, and the Owner and the Admin can change it.

## Where it applies

The setting decides the revenue month:

- in the revenue figures from Nio, from AI tools you connect with [DeskBoy MCP](/en/guides/etherly-insights), and from the [Data Access API](/en/guides/data-access-api);
- on owner statements.

It does not affect documents, VAT or myDATA. Your accountant's [document register](/en/guides/document-register) always goes by each document's issue date.

## The three options

The same example for all three: a stay 28/7–2/8, 5 nights, €500, with its document issued on the check-out day, 2/8.

### Check-out date

The booking's full revenue counts in the check-out month.

| Month | Revenue |
|-------|--------:|
| July | €0 |
| August | €500 |

### Document issue date

Revenue counts in the month the stay's document was issued. Here that's the check-out month, because the document was issued on 2/8. Until a document is issued, the booking counts in the check-out month.

| Month | Revenue |
|-------|--------:|
| July | €0 |
| August | €500 |

Had the document been an invoice to a business issued on 5/9, the full €500 would count in September.

### Per night

Revenue is split evenly across the nights of the stay, and each month gets the share for its own nights.

| Month | Nights | Revenue |
|-------|--------|--------:|
| July | 4 (28–31/7) | €400 |
| August | 1 (1/8) | €100 |

## Cancellation fees

Cancellation fees count in the month of cancellation, whichever option you choose. If you corrected the booking's departure, they count in the month of the corrected departure; if the cancellation date isn't known, in the month of departure.

## Changing the setting

<Steps>
  <Step title="Choose an option">
    Under **Settings → Advanced → Revenue basis**, choose the option you want.
  </Step>
  <Step title="Confirm">
    In the **Change the revenue basis?** dialog, press **Change**.
  </Step>
</Steps>

The new option applies from the 1st of next month, to bookings checking in from that day. Bookings with an earlier check-in count as before, even if they check out later. This way each booking counts whole on a single basis, and the change doesn't move bookings that have already started. Until then, the new option is marked **Starts** with the date, and the current one **In effect today**.

For example, if on 15/6 you change from "Check-out date" to "Per night", the new option applies from 1/7. A stay 28/6–3/7 still counts by "Check-out date", because it checked in before 1/7.

- **Cancel change**: cancels the change before it applies, and the current option stays. If you choose another option before the first one applies, the new one replaces the scheduled change.
- **Change history**: shows each earlier option, the dates it applied and who changed it.

After a change, an owner statement can include bookings counted on different revenue bases; the statement marks which one applies to which bookings.

## A stay across New Year

The setting concerns DeskBoy's revenue reports. Your business's accounting books, which your accountant keeps, have their own rule: for a stay 29/12–3/1, the revenue for the December nights belongs to the old year, even when the stay has one receipt dated January. The receipt stays in January's document register, with its own date. Your accountant applies the accounting-books rule.
