---
layout: default
slug: order-tracking
menu: user
title: Associate Sales Rep with WordPress User
---
This plugin comes with a feature that lets you associate a sales rep with a specific existing WordPress user. 

All you need to do is first make sure that they have an existing WordPress user account and then go to the **Sales Rep** page, click to edit the sales rep, and then choose the user you want from the **Sales Rep WP Username** field.

![Screenshot of assigning WordPress user to sales rep](/img/{{ page.slug }}/otp-sales-rep-wp-user.png)

Doing this will give your sales reps two extra ways of checking and managing their orders. 

First, if a sales rep is logged in with that WordPress user account, they can go to the page on which you've placed the sales rep tracking form ([block](../blocks-shortcodes/sales-rep-form-block) or [shortcode](../blocks-shortcodes/sales-rep-form-shortcode)) and immediately view all of the orders assigned to them. There will be no need to enter their sales rep ID and/or email address.

### Sales Rep Admin Dashboard

Second, it will create a new sales-rep-specific dashboard in the plugin admin. When the sales rep logs in with the associated WordPress user account, they will see a new menu in their WordPress admin called **Order Tracking**. 

This will bring them to a dashboard that shows them only their orders, so they can manage everything themselves. They can change statues, locations, notes, fields and everything the admin can in the regular dashboard, but only for those orders assigned to them, and with no access to the rest of the admin dashboard. They can also create new orders that will automatically be assigned to them.

![Screenshot of sales rep dashboard](/img/{{ page.slug }}/otp-sales-rep-dashboard.png)