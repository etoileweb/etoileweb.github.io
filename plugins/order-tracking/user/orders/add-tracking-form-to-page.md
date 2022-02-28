---
layout: default
slug: order-tracking
menu: user
title: Add Tracking Form to a Page
---
To add the tracking form to a page, you can use either the included Gutenberg block or shortcode.

For the Gutenberg block, on the page edit screen, just click the + button to add a new block, search for **tracking** and add the **Tracking Form** block to the page.

You will see an option in the right sidebar that lets you choose whether or not you want to show all orders. Choosing **Yes** will display all orders in a list, instead of the input to enter and search for an order number.

![Gif of adding the Tracking Form block](/img/{{ page.slug }}/otp-add-tracking-form-block.gif)

[More information about the block](../blocks-shortcodes/tracking-form-block).

You can also add the tracking form to your page using the following shortcode:

`[tracking-form]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

![Gif of adding the shortcode](/img/{{ page.slug }}/otp-add-tracking-form-shortcode.gif)

You can view more information and all the available shortcode attributes [here](../blocks-shortcodes/tracking-form-shortcode).

## Email Verification

If you'd like to add an extra layer of security to your tracking form, you can enable the **Email Verification** option found in the **Basic** area of the **Settings** page. This will make it so someone has to input both the order number and the email address associated with the order to view it.