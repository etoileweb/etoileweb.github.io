---
layout: default
slug: order-tracking
menu: user
title: Payment Settings
---
The Order Tracking plugin comes with a feature that lets offer order payment via PayPal directly on your site. To enable this, go to **Settings > Payment** and toggle on the switch for **Allow Order Payment By PayPal**.

There are several extra options that allow you to fine tune this feature:

### Default Post-Payment Status

What status, if any, should an order be set to after payment is received?

### PayPal Email Address

What email address is associated with the PayPal account?

### Pricing Currency

What currency are your orders priced in?

### "Thank You" Page URL

What page should customers be taken to after successfully completing a PayPal payment?

## Setting up Payment for an Order

After an order is created, either manually in the admin or via the customer order form, you can go to the order edit screen to update the payment details.

![Screenshot showing the payment section on the order edit screen](/img/{{ page.slug }}/otp-order-edit-payment.png)

If you would like to make the order available for payment, simply set **Payment Completed** to **No** and enter a price in the **Order Payment Price** field. Now, the next time that order is tracked, there will be an extra option to pay for it.

And, once it's paid for, it will be automatically marked as payment completed.