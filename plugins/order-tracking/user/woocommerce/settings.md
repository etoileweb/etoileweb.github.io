---
layout: default
slug: order-tracking
menu: user
title: WooCommerce Integration Settings
---
There are several extra settings that let you fine tune the WooCommerce integration available in this plugin.

![Screenshot of WooCommerce settings](/img/{{ page.slug }}/otp-woocommerce-1.png)

### WooCommerce Prefix

What prefix, if any, should be added to the automatically-generated WooCommerce order numbers?

### Disable WooCommerce Random Suffix

By default, our plugin adds a random string of characters to the WooCommerce order number. Toggle this option on to disable that feature.

### Show Tracking On Order Page

Should order status information from our plugin be displayed on the WooCommerce order page?

### Location Dropdown for WooCommerce Orders

Should a location dropdown be added to the WooCommerce order edit screen?

### Replace WooCommerce Statuses with Status Tracking Statuses

Should the statuses from our plugin replace the default WooCommerce statuses?

### Disable Revert WooCommerce Statuses on Deactivation

By default, when this plugin is deactivated, WooCommerce orders will have their statuses returned to one of the WooCommerce default statuses. Toggling this option on disables this feature (so the status is left unchanged). Using this option could result in orders with custom statuses being hidden from the WooCommerce admin orders table after deactivation.

### WooCommerce Order Statuses

There are several options here that let you choose a corresponding order status that you have created in our plugin to match with the default WooCommerce statuses. This will create a seamless sync and automatically update the statuses across both plugins at the same time (i.e. if you update the status of an order in our plugin, it will automatically update the status of the same order on the WooCommerce side to the chosen associated status). 

