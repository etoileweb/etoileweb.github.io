---
layout: default
slug: order-tracking
menu: user
title: Sales Rep Tracking Form
---
To add the sales rep tracking form to a page, you can use either the included Gutenberg block or shortcode.

For the Gutenberg block, on the page edit screen, just click the + button to add a new block and add the **Sales Rep Form** block to the page.

[More information about the block](../blocks-shortcodes/sales-rep-form-block).

You can also add the sales rep tracking form to your page using the following shortcode:

`[sales-rep-form]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

You can view more information and all the available shortcode attributes [here](../blocks-shortcodes/sales-rep-form-shortcode).

## Using the Form

When your sales rep visits this page, they can enter their ID to view a table with all of their existing orders.

![Screenshot of the front-end customer orders table](/img/{{ page.slug }}/otp-sales-rep-tracking-table.png)

You can find the sales rep ID by going to the **Sales Reps** page. The ID shows in the first column there.

![Screenshot of where to find the Customer ID](/img/{{ page.slug }}/otp-sales-rep-id.png)

### Email Verification

If you'd like to add an extra layer of security to your tracking form, you can enable the **Email Verification** option found in the **Basic** area of the **Settings** page. This will make it so the sales rep has to input their ID as well as their email address to view their orders.

## Linking to the Order Tracking Page

In the table that shows all the orders assigned to a sales rep, it will display the associated order number for each order. It is possible to make this number a link that goes directly to the tracking page for that order. To do this, you just have to go to the **Basic** area of the **Settings** page and fill in the URL of your tracking page (the page on which you have placed the tracking form block or shortcode) in the **Status Tracking URL** field.