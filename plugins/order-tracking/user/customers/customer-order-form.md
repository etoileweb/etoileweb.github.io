---
layout: default
slug: order-tracking
menu: user
title: Customer Order Form
---
The Order Tracking plugin comes with a feature that lets you place a customer order form on your website, which your customers can fill out to submit/create their own orders, which you can then update (status, etc.) in the admin.

For the Gutenberg block, on the page edit screen, just click the + button to add a new block and add the **Customer Order Form** block to the page.

[More information about the block](../blocks-shortcodes/customer-order-form-block).

You can also add the customer order form to your page using the following shortcode:

`[customer-order]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

You can view more information and all the available shortcode attributes [here](../blocks-shortcodes/customer-order-shortcode).

## Using the Form

When your customer visits this page, they will see a form that lets them fill in an order name and email address. 

![Screenshot of the front-end customer order form](/img/{{ page.slug }}/otp-customer-order-form.png)

## Custom Fields

If you would like to add extra fields to this form, you can easily do so by making use of the custom fields feature. See [here](../custom-fields) for more info about custom fields. You can make a field required by checking the **Required** box on the **Custom Fields** page in the admin

![Screenshot of custom fields tab](/img/{{ page.slug }}/otp-custom-fields-required.png)

## Customizing the Form and Order Process

There are several options that let you further customize the order form and its behaviour. You can go to **Settings > Premium > Customer Order Form** to find these.

### Default Order Status

What status, if any, should a newly-submitted order be set to?

### Allow Sales Rep Selection

Should an option to choose a sales rep be included in the customer order form?

### Assign Orders to Customers

With this enabled, orders submitted using the customer order form will be automatically assigned to a customer based on their email address.

### Order Number Prefix

Specify a prefix for the auto-generated order number for orders created using the customer order form.

### Order Number Suffix

Specify a suffix for the auto-generated order number for orders created using the customer order form.

### Default Sales Rep

Choose a default sales rep for all orders created using the customer order form (if not using the above option to enable sales rep selection).