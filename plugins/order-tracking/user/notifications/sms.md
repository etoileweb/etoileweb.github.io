---
layout: default
slug: order-tracking
menu: user
title: SMS Notifications
---
If you are using the [ultimate version](../premium/ultimate-benefits) of the plugin, you can also create SMS messages to be used as notifications. To do this, go to the **Notifications** area of the **Settings** page. 

Here there are a few options you need to set to make sure your SMS messages are sent.

- **Ultimate Plan Purchase Email**: The email used to purchase your ultimate plan subscription. Used to verify SMS requests are actually being sent from your site.
- **Country Code**: The country code that will be added to SMS notifications. If no country is specified, phone numbers for orders should start with +XXX (a plus sign followed by the country code), followed by a space or dash, or else the phone number will be assumed to be North American.
- **Admin Phone Number**: The phone number customer note and customer order notifications will be sent to, if they've been set to an SMS message in the **Premium** area of the **Settings** page.

![Screenshot of SMS options](/img/{{ page.slug }}/otp-sms-options.png)

## Create SMS Notifications

Below this, you will see a table with all your existing SMS messages as well as a button to add a new one.

![Screenshot of the SMS notifications table](/img/{{ page.slug }}/otp-sms-table.png)

The process is similar to creating an email. You need to fill in the following for each:

- **Name**: The name you want to give to your SMS message. This is used for you to identify the message when choosing which one you want to assign to a status or other notification.
- **Message**: The message or content of the SMS that will be sent.

![Screenshot of editing an SMS message](/img/{{ page.slug }}/otp-sms-edit.png)

## Order-Specific Information

You can include order-specific information in the SMS message by making use of one of the following shortcodes:

`[order-name]` The name of the order.

`[order-number]` The order number.

`[order-status]` The order status.

`[order-notes]` The public notes for the order.

`[customer-notes]` The customer notes for the order.

`[order-time]` The time the order was created.

`[customer-name]` The name of the assigned customer for the order.

`[customer-id]` The ID of the assigned customer for the order.

`[sales-rep]` The assigned sales rep for the order.

`[custom-field]` You can also include a custom field value in the email by placing the slug of the custom field within the square brackets. For example, if the slug of your custom field is **order-quantity**, then you would use `[order-quantity]`

When you're done creating/editing your emails, make sure to click the **Save Changes** button to save your changes.