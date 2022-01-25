---
layout: default
slug: ultimate-product-catalog
menu: user
title: WooCommerce FAQ
---
## I have WooCommerce Sync enabled, but my products aren't syncing

Try the following troubleshooting steps:

1. Make sure you have the WooCommerce plugin activated.
2. Disable and then re-enable the **WooCommerce Sync** option in our plugin.
3. Make a change to a product in our plugin and then save it. This should force a new sync.
4. Create a new product in our plugin. Does that one sync? If so, the issue is likely with a specific product, and likely with the way it's set up on the WooCommerce side.
    - Are you using any (other) third-party WooCommerce plugins/add-ons? If so, it could be that the meta data they add to a product is blocking the sync. If, as a test, you temporarily deactivate said plugin, does the sync then work? 
    - Have you set up any special **attributes** in WooCommerce? If so, try manually creating a custom field in our plugin to match. 

## Custom fields are not syncing with WooCommerce attributes

Have you set up any special **attributes** in WooCommerce? If so, try manually creating a custom field in our plugin to match. 

Alternatively, try creating a new product in our plugin and assigning a custom field value to it. This should automatically sync over to WooCommerce as a new attribute. Then, you can move over to the WooCommerce side and modify the attribute as you need.

## Can I disable the item count that shows in the cart?

Yes, on the **Settings > WooCommerce** page, there is an option for this called **Disable Cart Item Count**.

## Can I make it so the button in the cart pane goes to the cart page instead of the checkout page?

Yes, on the **Settings > WooCommerce** page, you can use the **WooCommerce Cart Page** option to choose which page you want it to go to.

## Can I make change the breadcrumb on the WooCommerce product page to link back to the catalog instead of WooCommerce's shop page?

This is possible. On the **Settings > WooCommerce** page, you can use **WooCommerce Back Link** option to do this. Please note that **WooCommerce Product Page** must be enabled for this to work.

For help and support, please see [here](../support).