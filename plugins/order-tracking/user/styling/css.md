---
layout: default
slug: order-tracking
menu: user
title: Custom CSS
---
In certain cases, you may not be able to achieve exactly what you want using only the styling options. To further customize the look and layout of your order tracking pages, you can add some of your own CSS.

We've added a **Custom CSS** input area to the top of the **Basic** settings page, which you can use to add your custom CSS. If you'd prefer, you can also/instead use the Additional CSS area in your theme's customizer for this. 

*Please note that using custom CSS to modify the look of your order tracking pages requires knowledge of CSS. Attempting to modify your order tracking pages without this knowledge may result in messing up the layout and even possibly altering/removing certain functionality.*

As an example, let's say that you wanted to make the font size bigger in the main tracking form. The following CSS would help you to achieve that:

`.ewd-otp-order-tracking-form-div {
  font-size: 1.5em;
}`

![Gif of adding custom CSS](/img/{{ page.slug }}/otp-custom-css.gif)

## CSS Selectors

Some common CSS selectors from the plugin are:

`.ewd-otp-form` Main overall container for the order tracking form

`.ewd-otp-order-tracking-form-div h3` Tracking form title

`.ewd-otp-tracking-form label` Tracking form input label

`.ewd-otp-tracking-form input` Tracking form input field

`.ewd-otp-submit` Tracking form submit button

`.ewd-otp-tracking-results` Main overall container for the tracking results

`.ewd-otp-tracking-graphic` The tracking graphic/status bar

`.ewd-otp-tracking-results-field` Container for each row on the tracking results page

`.ewd-otp-tracking-results-label` Label for each row on the tracking results page

`.ewd-otp-tracking-results-value` Value for each row on the tracking results page

`.ewd-otp-tracking-results-value iframe` The tracking map

`.ewd-otp-status-label` Selector for each row of the past statuses area on the tracking results page 

`.ewd-otp-statuses-header` Selector for each entry in the header row of the past statuses area on the tracking results page

`.ewd-otp-statuses` Selector for each entry in the rest of the rows in the past statuses area on the tracking results page

`.ewd-otp-print-results` The "Print" button on the tracking results page

`.ewd-otp-matching-orders` The table on the customer or sales rep tracking results page

`.ewd-otp-customer-order-form` Main oversall container for the customer order form

`.ewd-otp-customer-order-form-field` Selector for each row in the customer order form

`.ewd-otp-customer-order-form-label` Input label in the customer order form

`.ewd-otp-customer-order-form-value` Input field container in the customer order form

`.ewd-otp-submit` Submit button in the customer order form