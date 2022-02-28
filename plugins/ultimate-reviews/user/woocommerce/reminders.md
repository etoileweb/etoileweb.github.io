---
layout: default
slug: ultimate-reviews
menu: user
title: WooCommerce Reviews Reminders 
---
The WooCommerce review integration also comes with the ability to send reminders emails to people who have purchased any product, or a specific product, to ask them to review the product(s).

To configure your reminders, go to the **WooCommerce** area of the **Settings** page and scroll down to the **REVIEW REMINDERS EMAILS** section. Here you will see a table with all your existing reminders as well as a button to add a new one.

![Screenshot of WooCommerce review reminder settings](/img/{{ page.slug }}/urp-woocommerce-2.png)

The process is the same to add or edit a reminder. You need to fill in the following for each:

- **Reminder ID**: Use this to assign a unique ID to the reminder.
- **Email to Send**: Choose which email to send. Emails can be created using the setting just below the reminders table.
- **Reminder Interval and Reminder Unit**: Use these to set the amount of time after a purchase that you wish to send the reminder.
- **Status**: Choose which status an order has to be set to in order for the reminder to be sent.

## Email Messages

Just below the reminders table is where you can create the email messages that can be sent via the reminders. In the table here you'll see all your existing emails as well as a button to add a new one. The process is the same to add or edit an email. You need to fill in the following for each:

- **Message ID**: Use this to assign a unique ID to the email.
- **Message Subject**: Provide a subject for the email that will be sent to the customer.
- **Message**: Write the content for the email that will be sent to the customer. You can use `[section]...[/section]` and `[footer]...[/footer]` to split up the content of your email. You can also include a link button, like so: `[button link='LINK_URL_GOES_HERE']BUTTON_TEXT[/button]`, and a link to review each individual item in an order with: `[review-items link='LINK_URL_TO_SUBMIT_REVIEW_PAGE']`. You can also put `[purchase-date]` into the message body or subject, to include the purchase date.

Just below the emails table, you will find an option to send a sample email. You can use this to test the email messages you've created.

### Email Styling

The plugin also comes with a set of styling options that let you customize the colors of the various elements in the email messages.

![Screenshot of WooCommerce review reminder styling options](/img/{{ page.slug }}/urp-woocommerce-3.png)