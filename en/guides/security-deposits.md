---
title: 'Damage deposits'
description: "What a damage deposit is, how the hold on the guest's card works and why it costs less than a charge and a refund, connecting Stripe from Connections, a new request from the booking, sending by email, “Copy guest link”, cancelling a request, the deposit after Online Check-In, what the guest sees and approves, automatic release, hold renewals for stays longer than 7 days, “Extend hold” to check for damage with a new date and an optional reason, charging for damage and releasing the remainder, releasing without a charge, the damage document, checking a pending operation, booking cancellation, notifications, who can do what, disconnecting Stripe, and which plans include it."
---

## What a damage deposit is

With a damage deposit you ask the guest to place a hold on their card for the stay. The amount is **not collected**: it stays on hold and is released automatically after departure. If damage occurs, you charge up to the deposit amount. The money goes to your own Stripe account.

---

## Why a hold and not a charge

If you charged the deposit amount and refunded it after departure, you would pay a fee for a payment that is returned in the end: Stripe does not return the fee of the original charge when you refund. With a hold the amount is not collected, so you pay a fee only if you charge for damage, and only on the amount you charge.

<Note>
This applies to Stripe's standard pricing. If you have a custom pricing agreement with Stripe, check its terms.
</Note>

---

## Connecting Stripe

Deposits are charged through your own Stripe account, so the money goes straight to you.

1. Open **Settings → Connections** and, on the **Stripe — Charges and holds** card, press **Connect**.
2. Complete your business details in Stripe.
3. When you are back in DeskBoy, the **Configure** dialog opens with the connection status. Once it is complete, the **Stripe** row under **Connected Applications** shows **Connected**; if not yet, press **Refresh status** in the same dialog.

If the row shows **Information update required**, press **Configure** and then **Continue to Stripe** to complete whatever Stripe asks for.

<Note>
The guest enters their card only in Stripe's secure payment form. DeskBoy does not see the full card number.
</Note>

---

## New deposit request

Open the booking in **Bookings** and, in the **Customer** column, press **Damage deposit**. The form opens with the booking already selected; you only enter the amount.

The request sends nothing by itself: the card form goes out in the next step, from the deposit's details, with **Send by email** or **Copy guest link**. The hold happens only through this DeskBoy form, not through Airbnb, Booking or any other channel.

Each booking has one deposit. New requests are made for bookings that are not cancelled and whose check-out has not passed.

---

## Sending it to the guest

From the deposit's details:

- **Send by email:** the link goes to the booking's email. If you changed the guest's email on the booking, it goes to the new one.
- **Copy guest link:** to send it in a message through the booking channel.

The link is personal to the booking and stays the same until the deposit is completed.

If you use **Online Check-In**, the deposit form appears to the guest as soon as they complete check-in.

---

## Cancelling a request

If the guest has not approved the deposit yet, press **Cancel request** in the details. The guest's link stops working, and you can request a new deposit from the booking.

---

## What the guest sees

The guest sees the property, the amount, the **Hold ends** date and the deposit terms, in Greek, English, German, French, Dutch or Italian. They accept the terms, enter their card and approve the hold; their bank may ask them to confirm on their phone. After approval they receive a confirmation email.

---

## Automatic release

In the deposit's details you see the **Hold ends** date and, once the guest approves, **Hold started**. When the hold ends, the automatic release takes place: DeskBoy requests the release of the amount and the guest is notified by email. The guest's bank decides when the amount is available on their card again.

### Hold renewals

A bank keeps a hold for a limited time, usually up to 7 days, and less for some cards. When the deposit needs to last longer, for example for longer stays, DeskBoy renews the hold automatically before it expires, for the same amount, until the automatic release date, as the guest has accepted. During a renewal two holds may appear on their card for a while. If the hold cannot be renewed automatically, for example because the guest's bank asks the guest to confirm again (3D Secure), you receive an email and the deposit appears under **Action required**. The current hold is valid until it expires, so until then you can charge for any damage done to the property. To extend the hold until the automatic release date, send the guest the form from the deposit's details, with **Send by email** or with **Copy guest link** to send it however you prefer.

---

## Extending the hold

If you need time to check for possible damage, press **Extend hold** in the deposit's details, set the new date and, if you want, a reason. The guest is notified by email. You can extend the hold up to 7 days after the original date without a new approval, because the guest accepted this with their approval. If the new date requires extending the hold with the bank, what is described under “Hold renewals” applies.

In the **Extend hold** dialog you pick the new date under **Extend hold until**, write, if you want, a **Reason sent to the guest (optional)** and press **Extend**; **Back** closes it without a change.

---

## Charging for damage

Press **Charge for damage**, enter the amount, up to the deposit amount, and the **reason**. The amount you charge is final and includes VAT and any other taxes; the damage document is issued for this amount. The guest sees the reason in the email they receive about the charge. Only one charge can be made from each hold; the remaining amount is released automatically.

If you don't need to wait for the automatic release, press **Release** in the deposit's details. The amount is released without a charge and the guest is notified by email.

### Damage document

Issue the document in your invoicing provider and register its details in the deposit's details. The **No document registered** counter on the Damage deposits page shows the charges that do not have a document yet.

---

## Pending operation

Rarely, Stripe takes a while to confirm a charge or a release, and the deposit shows **Review pending operation**. Press **Check Stripe** to look up the outcome. If the check finds no outcome, the owner or an admin can, after checking the deposit in the Stripe Dashboard, press **Mark as failed** with a reason, so that new actions are allowed.

---

## Booking cancellation

If the booking is cancelled, a request the guest has not approved yet is cancelled, and an active hold is released automatically shortly after the cancellation.

---

## Notifications

When the guest approves the deposit, for the first time or again, you receive an email that the amount has been held. The owner and the admins receive an email when a deposit needs action, for example when the guest disputes a charge with their bank. On the Damage deposits page, the **Action required** counter shows the deposits waiting for you.

---

## Who can do what

| Role | Can |
|---|---|
| Owner, Admin | Everything: connect Stripe, requests, sending, extend hold, charge, release, document |
| User | View, new request, send the link, cancel the request before the guest approves |
| Accountant | View |

Charging, releasing and extending the hold are limited to the owner or an admin, because they concern the guest's money.

---

## Disconnecting Stripe

Under **Connected Applications**, press **Configure** on the **Stripe** row and then **Disconnect Stripe**. If there are active deposits, after disconnecting you manage them from the Stripe Dashboard. Holds will expire unless captured in time.

---

## Availability

Damage deposits are available on Business and above.
