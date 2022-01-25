---
layout: default
slug: order-tracking
menu: user
title: tracking-form Shortcode
---
You can add your tracking form to a page using the following shortcode:

`[tracking-form]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

![Gif of adding the shortcode](/img/{{ page.slug }}/otp-add-tracking-form-shortcode.gif)

## Attributes

The tracking-form shortcode takes the following attributes:

`show_orders` Setting this to "yes" will display all orders in a list, instead of the input to enter and search for an order number. Example: `[tracking-form show_orders="yes"]`

`order_form_title` Use this to specify the title you want to show for the order form.

`order_instructions` Use this to specify the instruction text that displays below the title.

`order_field_text` Use this to specify the text of the label for the order number input.

`email_field_text` Use this to specify the text of the label for the email address input.

`submit_text` Use this to specify the text of the submit button.

`notes_submit` Use this to specify the text of the label for the submit button.

Example:

`[tracking-form order_form_title="My Tracking Page" order_instructions="Please enter your order number below to track it." order_field_text="Order number" email_field_text="Email address" submit_text="Track" notes_submit="Use this button to track your order."]`
