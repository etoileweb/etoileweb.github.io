---
layout: default
slug: order-tracking
menu: user
title: Basic Settings
---
The following options are available by going to **Settings > Basic**

### Custom CSS

In this space, you can add custom CSS styles to your order tracking pages. For more info, see [here](../styling/css).

### Order Information Displayed

Choose which elements you would like to display on the tracking results page.

### Hide Blank Fields

Should fields which don't have a value (e.g. customer name, custom fields) be hidden if they're empty?

### Form Instructions

The instructions that will display above the order tracking form.

### Date/Time Format

The format to use when displaying dates. Possible options can be found [here](https://www.php.net/manual/en/datetime.format.php).

### Order Email Frequency

How often should emails be sent to customers about the status of their orders? More info about notifications can be found [here](../emails/notifications).

### Disable AJAX Reloads

By default, AJAX is used to display tracking results without reloading the page. Toggling on this option disables that feature?

### New Window

Should tracking results open in a new window? (Doesn't work with AJAX reloads.)

### Display *Print* Button

Should a **Print** button be added to tracking form results, so that visitors can print their order information more easily?

### Email Verification

Do visitors need to also enter the email address associated with an order to be able to view order information?

### Google Maps API Key

If you're displaying a map of your order locations (using the **Tracking Map** checkbox in the **Order Information** setting above), Google requires an API key to use their maps. [Get an API key](https://developers.google.com/maps/documentation/javascript/get-api-key).

### Status Tracking URL

The URL of your tracking page. Required if you want to include a tracking link in your message body, on the WooCommerce order page, etc.

### Use WP Timezone

By default, the timestamp on status updates uses your server's timezone. Enabling this will make it display (in the admin and on the front-end tracking page) using the timezone you have set in your WordPress General Settings instead. 