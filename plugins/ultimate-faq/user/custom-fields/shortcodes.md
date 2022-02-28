---
layout: default
slug: ultimate-faq
menu: user
title: Displaying Custom Fields via Shortcode
---
By using dedicated shortcodes, it's possible to display custom field values in places other than the catalog page thumbnails or the Additional Information tab on the product page.

When you [created your custom field](create), you gave it a unique slug. This can be used to call the custom value by wrapping it in square brackets, like so: `[custom-field-slug-1]`

For this to work, you need to also make sure that you have not toggled on the **Disable Custom Slugs Conversion** option (in the [Premium area of the Settings page](../settings/premium)).

This can be used in several different places, including in the product description and in [custom tabs](../product-page/custom-fields).

![Screenshot of the custom field shortcode in admin](/img/{{ page.slug }}/upcp-custom-fields-6.png)

![Screenshot of the custom field shortcode in product description](/img/{{ page.slug }}/upcp-custom-fields-7.png)