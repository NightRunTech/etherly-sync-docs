---
title: 'Damage deposits'
description: "What a damage deposit is, how the hold on the guest's card works and why it costs less than a charge and a refund, connecting Stripe from Connections, a new request from the booking, sending by email, copying the link and opening on a tablet, the deposit after Online Check-In, what the guest sees and approves, automatic release and the countdown, hold renewals for stays longer than 7 days, pausing to check for damage, charging for damage and releasing the remainder, the damage document, booking cancellation, notifications, who can do what, disconnecting Stripe, and which plans include it."
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

1. Open **Settings → Connections** and, on the **Stripe — Damage deposits** card, press **Connect**.
2. Complete your business details in Stripe.
3. When you are back in DeskBoy, the **Configure** dialog opens with the connection status. Once it is complete, the **Stripe** row under **Connected Applications** shows **Connected**; if not yet, press **Refresh status** in the same dialog.

If the row shows **Information update required**, press **Configure** and then **Continue to Stripe** to complete whatever Stripe asks for.

<Note>
The guest enters their card only in Stripe's secure payment form. DeskBoy does not see the full card number.
</Note>

---

## New deposit request

Open the booking in **Bookings** and, in the **Customer** column, press **Damage deposit**. The form opens with the booking already selected; you only enter the amount.

Each booking has one deposit. New requests are made for bookings that have not been cancelled.

---

## Sending it to the guest

From the deposit's details:

- **Send by email:** the link goes to the booking's email. If you changed the guest's email on the booking, it goes to the new one.
- **Copy guest link:** to send it in a message through the booking channel.
- **Open on tablet:** opens the guest page, so the guest can approve on the front-desk device.

The link is personal to the booking. Each new link replaces the previous one, which stops working.

If you use **Online Check-In**, the deposit form appears to the guest as soon as they complete check-in.

---

## What the guest sees

The guest sees the property, the amount, the automatic release date and the deposit terms, in Greek, English, German, French, Dutch or Italian. They accept the terms, enter their card and approve the hold; their bank may ask them to confirm on their phone. After approval they receive a confirmation email.

---

## Automatic release

In the deposit's details you see the **automatic release** date and a countdown. At that moment DeskBoy requests the release of the amount and the guest is notified by email. The guest's bank decides when the amount is available on their card again.

### Hold renewals

A bank keeps a hold for a limited time, usually up to 7 days, and less for some cards. The exact expiry is shown as **Bank hold expiry**. When the deposit needs to last longer, for example for longer stays, DeskBoy renews the hold automatically before it expires, for the same amount, until the automatic release date, as the guest has accepted. During a renewal two holds may appear on their card for a while. If the hold cannot be renewed automatically, for example because the bank asks for a new approval, the guest receives an email to approve it again.

---

## Pausing to check for damage

If you need time to check for possible damage, press **Pause automatic release**. The countdown stops and the amount stays on hold for as long as the bank hold lasts. Pausing does not extend the bank hold expiry, because the bank sets it.

---

## Charging for damage

Press **Charge for damage**, enter the amount, up to the deposit amount, and the **reason**. The guest sees the reason in the email they receive about the charge. Only one charge can be made from each hold; the remaining amount is released automatically.

### Damage document

Issue the document in your invoicing provider and register its details in the deposit's details. The **No document registered** counter on the Damage deposits page shows the charges that do not have a document yet.

---

## Booking cancellation

If the booking is cancelled, a request the guest has not approved yet is cancelled, and an active hold is released automatically shortly after the cancellation, unless you have paused the release to check for damage.

---

## Notifications

The owner and the admins receive an email when a deposit needs action, for example when the guest disputes a charge with their bank. On the Damage deposits page, the **Action required** counter shows the deposits waiting for you.

---

## Who can do what

| Role | Can |
|---|---|
| Owner, Admin | Everything: connect Stripe, requests, sending, pause, charge, release, document |
| User | View, new request, send the link, cancel before the guest approves |
| Accountant | View |

Charging, releasing and pausing are limited to the owner or an admin, because they move the guest's money.

---

## Disconnecting Stripe

Under **Connected Applications**, press **Configure** on the **Stripe** row and then **Disconnect Stripe**. If there are active deposits, after disconnecting you manage them from the Stripe Dashboard. Holds will expire unless captured in time.

---

## Availability

Damage deposits are available on Business and above.
