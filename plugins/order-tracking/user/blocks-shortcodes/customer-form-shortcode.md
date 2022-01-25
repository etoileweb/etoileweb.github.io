---
layout: default
slug: order-tracking
menu: user
title: customer-form Shortcode
---
You can add a customer tracking form to a page using the following shortcode:

`[customer-form]`

For more info about creating and working with customers, see [here](../customers).

## Attributes

The customer-form shortcode takes the following attributes:

`order_form_title` Use this to specify the title you want to show for the order form.

`order_instructions` Use this to specify the instruction text that displays below the title.

`order_field_text` Use this to specify the text of the label for the customer ID input.

`email_field_text` Use this to specify the text of the label for the email address input.

`submit_text` Use this to specify the text of the submit button.

Example:

`[customer-form order_form_title="My Customer Tracking Page" order_instructions="Please enter your customer ID below to track your orders." order_field_text="Customer ID" email_field_text="Email address" submit_text="Track"]`