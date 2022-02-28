---
layout: default
slug: order-tracking
menu: user
title: Email Notifications
---
Now that you've created your emails, this page will show you how to configure the notifications in the plugin.

## Statuses

The main trigger for email notifications in this plugin is status updates. As such, you need to assign an email to each status. To do this, go to **Settings > Statuses**. For each created status, there is a dropdown that includes all the [emails you created in this plugin](create) as well as any [emails you have created using the Ultimate WP Mail plugin](ultimate-wp-mail).

![Screenshot of the Emails settings page](/img/{{ page.slug }}/otp-settings-statuses-emails.png)

You can choose a different email for each status or the same email for several different statuses.

***Note***: There is one extra step to make sure your notifications get sent out on status update. If you go to the **Settings > Basic** page, there is an option called **Order Email Frequency**. If you would like an email notification to be sent out on every status update, then you need to set this to **On Change**. Otherwise, you can set it to only when a new order is created or to never.

![Screenshot of the order email frequency setting](/img/{{ page.slug }}/otp-order-email-frequency.png)

## Other Email Notifications

There are two other email notification types available in the plugin and they are both for the admin. These can be found in the **Premium** area of the Settings page. As with the statuses, both can be either an email created in the plugin or in Ultimate WP Mail.

- **Customer Notes Email**: Lets you choose which email you want to send to the admin when the customer note is updated for an order.

- **Customer Order Email**: Lets you choose which email you want to send to the admin when a new submission is received via the customer order form.

![Screenshot of the email notification options](/img/{{ page.slug }}/otp-email-notifications-options.png)