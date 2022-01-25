---
layout: default
slug: order-tracking
menu: user
title: Ultimate WP Mail
---
If you would prefer to use a more visual builder for your emails, you can make use of the free [Ultimate WP Mail](https://wordpress.org/plugins/ultimate-wp-mail) plugin, which integrates fully with the order tracking plugin.

To create an email in this plugin, open your WordPress admin and go to **Emails > Add New**.

First, give your email a subject.

From there, you can add the content of your email using the visual builder. There are several preset templates available for you to use, or you can start from scratch by clicking one of the column buttons at the top.

You will then see that each content area can be edited separately using the familiar WordPress WYSIWYG (what you see is what you get) editor. 

There are also separate styling options for each specific email.

![Gif of creating email in Ultimate WP Mail](/img/{{ page.slug }}/otp-uwpm-1.gif)

## Order-Specific Information

The Ultimate WP Mail plugin comes with a special set of variables that you can use to dynamically include order-specific information in your email.

To make use of these, just open the editor for a specific content area, click on **Email Variables** and choose **Order Tracking Tags**. You'll be presented with a dropdown from which you can choose any of the following:

- Order Name
- Order Number
- Order Status
- Order Notes
- Order Customer Notes
- Order Updated Time
- Tracking Link
- Customer Name
- Customer ID
- Sales Rep Name
- *Custom Fields*: There will be an extra entry in this list for each existing custom field that you have. It will display the value for that custom field assigned to the chosen order. 

![Gif of adding order tracking variables to email in Ultimate WP Mail](/img/{{ page.slug }}/otp-uwpm-2.gif)

Once you're done adding in your content and order tracking variables, make sure to click the **Save** button on the right side of the screen, to save your email.

You can now learn how to [use this email for your statuses and notifications](notifications).