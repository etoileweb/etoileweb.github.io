---
layout: default
slug: order-tracking
menu: user
title: Create and Edit Custom Fields
---
To create or edit a custom field, go to the **Custom Fields** page. Here you will see a table with all your existing custom fields as well as a button to add a new one.

![Screenshot of the Custom Fields tab](/img/{{ page.slug }}/otp-custom-fields-tab.png)

The process is the same to add or edit a field. You need to fill in the following for each:

- **Name**: The name you want to give to your custom field. This will display as the label for the field on your tracking page and in the customer order form.
- **Slug**: Give the custom field a unique slug. This should contain only letters, numbers and hyphens. It will be used to identify the field behind the scenes, when the plugin queries it, as well as to include custom field data in notification [emails](../emails).
- **Type**: Choose the type of custom field you want. This decides how you will input the value for this field on the order edit screen. So, for example, if you want to be able to insert anything, then choose text or or textarea. If would like there to be a set list of values, but will need to assign more than one value for each order, then you will want to use checkbox. If you would like to restrict it to only one value per order, then use radio or dropdown. There are also types for image, number, link, file upload and date/time.
- **Input Values**: If you are using the checkbox, radio or dropdown type, then you will need to provide input values here. These are the options from which you will be able to select on the order edit screen. Comma-separate your list, leaving no space after each comma. For example: *Giraffe,Moose,Goose,Lion*
- **Applicable to**: This sets whether this field should be used for orders, customers or sales reps. 
- **Options**
    - **Required**: Checking this makes the field required in the customer order form.
    - **Admin Display?**: Checking this adds the field as column to the table on the **Orders** admin screen.
    - **Front-End Display?**: Check this if you want the field and the associated value to show on the tracking page.
- **WooCommerce Equivalent**: If you are using the [WooCommerce integration](../woocommerce), you can use this to select which element from WooCommerce, if any, this field should match to.

When you're done creating/editing your fields, make sure to click the **Update Fields** button to save your changes.

To learn about using custom fields with orders, see [here](orders).

