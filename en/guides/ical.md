---
title: "iCal Calendar"
description: "An iCal link per property, per group or for all properties that shows bookings and availability to calendars and partners: turning it on under Connections, the settings Period, Cancelled bookings, Times, the Availability link and the optional per-property Link with guest details, the Copy button, and adding the link to Google Calendar and Apple Calendar."
---

# iCal Calendar

Give partners a link that shows the bookings and availability of each property. Anyone with the link can see what it contains, without signing in to DeskBoy.

The feed includes the bookings, shown as **Reserved**, and the dates on which the property is not available. With a Hosthub connection it also includes the PMS blocks, such as cleaning, repairs or personal use, shown as **Unavailable**. The feed's texts are in English, because calendars and partners of any language read it.

## Turning it on

1. Go to **Settings → Connections** and, under **Apps**, click **Enable** on the **iCal Calendar** card. The page with the settings and links opens.
2. While it is on, it appears under **Connected apps** with a **Configure** button. To turn it off, click the bin icon on the same row: the links stop responding immediately, and stay the same if you turn it on again.

The page is available to the account owner and its admins.

## Settings

- **Period**: **Upcoming bookings only** (default) or **Including the last 12 months**. Calendars truncate or slow down on very large feeds, which is why history is limited to 12 months.
- **Cancelled bookings**: **Hidden** (default) or **Shown as cancelled**, with a "cancelled" marker in the title.
- **Times**: **All-day events** (default), as the channels send them, or **With check-in and check-out times**. In the second case you set **Check-in** and **Check-out**. The time zone is that of each property.

Each choice is saved immediately and a **Saved** indicator appears. The changes apply to every link.

## Links

The list shows the **All properties** link first, then the properties by group, and finally the properties with **No group**. Each group also has its own link covering all its properties. All of these links show only that a date is reserved, with no guest details.

- **Copy**: copies the link.
- **Activity** (pulse icon; on a phone, a line under the link): when a calendar last read the link and how many times in total. A calendar reads every few hours, so many reads a day mean the link has been handed out widely. After **New link** the count starts over.
- **New link** (refresh icon): creates a new link after you confirm. The previous one stops responding immediately, so give the new one to whoever uses it. It is also available for the link with guest details.

### Link with guest details

Each property has the **Link with guest details** switch. When you turn it on, a dialog explains what the link contains and, with **Enable**, a second link **With guest details** appears next to the **Availability** link. The second link shows the guest name, channel, number of guests, country and booking reference. It does not show email, phone or amounts.

Anyone with this link can see the guest details, without signing in to DeskBoy. Give it only to someone who needs it for this property, and make sure you know where this information is shared. The group links and **All properties** have no version with details.

To revoke it, turn the switch off: the link stops responding immediately. If you turn it on again you get a new link; the old one does not work again. Turning it on and off is recorded in the activity history.

DeskBoy updates the feed immediately, as soon as a booking changes. Calendars, however, re-read it on their own schedule, often every few hours, so changes show up there with a delay. Google Calendar can take several hours to refresh and cannot be hurried; in Apple Calendar you set the subscription refresh frequency yourself.

## Adding it to a calendar

- **Google Calendar** (desktop): under Other calendars click **+ → From URL** and paste the link.
- **Apple Calendar** (Mac): **File → New Calendar Subscription** and paste the link. On iPhone: **Settings → Calendar → Accounts → Add Account → Other → Add Subscribed Calendar**.
- **Another PMS or channel manager**: paste the property's link into that property's iCal import setting.
