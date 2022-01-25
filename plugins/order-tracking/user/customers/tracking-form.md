---
layout: default
slug: order-tracking
menu: user
title: Customer Tracking Form
---
To add the customer tracking form to a page, you can use either the included Gutenberg block or shortcode.

For the Gutenberg block, on the page edit screen, just click the + button to add a new block and add the **Customer Form** block to the page.

![Gif of adding the Customer Form block](/img/{{ page.slug }}/otp-add-customer-form-block.gif)

[More information about the block](../blocks-shortcodes/customer-form-block).

You can also add the customer tracking form to your page using the following shortcode:

`[customer-form]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

You can view more information and all the available shortcode attributes [here](../blocks-shortcodes/customer-form-shortcode).

## Using the Form

When your customer visits this page, they can enter their ID to view a table with all of their existing orders.

![Screenshot of the front-end customer orders table](/img/{{ page.slug }}/otp-customer-tracking-table.png)

You can find the customer ID by going to the **Customers** page. The ID shows in the first column there.

![Screenshot of where to find the Customer ID](/img/{{ page.slug }}/otp-customer-id.png)

### Email Verification

If you'd like to add an extra layer of security to your tracking form, you can enable the **Email Verification** option found in the **Basic** area of the **Settings** page. This will make it so the customer has to input their ID as well as their email address to view their orders.

## Linking to the Order Tracking Page

In the table that shows all the orders assigned to a customer, it will display the associated order number for each order. It is possible to make this number a link that goes directly to the tracking page for that order. To do this, you just have to go to the **Basic** area of the **Settings** page and fill in the URL of your tracking page (so the page on which you have placed the tracking form block or shortcode) in the **Status Tracking URL** field.