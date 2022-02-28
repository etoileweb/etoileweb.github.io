---
layout: default
slug: order-tracking
menu: user
title: customer-order Shortcode
---
If you're using the premium version of the plugin, then you can use the following shortcode to display a form that lets people submit their own orders:

`[customer-order]`

For more info about the customer order form, see [here](../customers/customer-order-form).

## Attributes

This shortcode takes the following attributes:

`customer_name_field_text` Use this to specify the text of the label for the customer name input.

`customer_email_field_text` Use this to specify the text of the label for the email address input.

`customer_notes_field_text` Use this to specify the text of the label for the notes input.

`submit_text` Use this to specify the text of the submit button.

Example:

`[customer-order customer_name_field_text="Enter your name here" customer_email_field_text="Enter your email address here" customer_notes_field_text="Please add any notes you have here" submit_text="Submit Your Order"]`
