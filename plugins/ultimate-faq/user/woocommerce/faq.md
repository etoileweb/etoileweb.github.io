---
layout: default
slug: ultimate-faq
menu: user
title: Troubleshooting WooCommerce FAQs
---
## There is no FAQs tab on my WooCommerce product page

1. Make sure you've [enabled WooCommerce FAQs](index).
2. Make sure you've [added FAQs to that product](add).
3. Check to see if you have any other plugins that modify the WooCommerce product page. In rare instances, instead of adding their own content to the existing content, some plugins remove all existing content and replace it with their own. If you think this might be the case, try deactivating your other WooCommerce extension to see if that makes any difference.
4. Do you have a custom theme designed for WooCommerce? If so, does it have any product-page-specific options? If so, try disabling those options as a test. If that doesn't help, you can temporarily activate a default WordPress theme. If the FAQs tab then shows, contact your theme author to ask if they have any code added to remove custom tabs or if they are doing something similar to the aforementioned plugins and replacing the existing content.

## I've created an FAQ category with the same name as a product and added FAQs to that category, but my FAQs still aren't showing on the WooCommerce product page

Are there any special characters in the name of your product (e.g. apostrophe, slash, number sign, etc.)? Sometimes these are rendered differently across WordPress and it can make it so the match is not made between our plugin and WooCommerce. If you do a test and simplify the name of your product (and the associated FAQ category) to include no special characters, does it then work/show?

For help and support, please see [here](../support).