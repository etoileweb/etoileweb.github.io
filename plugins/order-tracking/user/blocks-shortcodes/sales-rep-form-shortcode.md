---
layout: default
slug: order-tracking
menu: user
title: sales-rep-form Shortcode
---
You can add a sales rep tracking form to a page using the following shortcode:

`[sales-rep-form]`

For more info about creating and working with sales reps, see [here](../sales-reps).

## Attributes

The sales-rep-form shortcode takes the following attributes:

`order_form_title` Use this to specify the title you want to show for the order form.

`order_instructions` Use this to specify the instruction text that displays below the title.

`order_field_text` Use this to specify the text of the label for the sales rep ID input.

`email_field_text` Use this to specify the text of the label for the email address input.

`submit_text` Use this to specify the text of the submit button.

Example:

`[sales-rep-form order_form_title="My Sales Rep Tracking Page" order_instructions="Please enter your sales rep ID below to track your orders." order_field_text="Sales Rep ID" email_field_text="Email address" submit_text="Track"]`