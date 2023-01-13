---
layout: default
slug: ultimate-product-catalog
menu: user
title: upcp-popular-products Shortcode
---
The plugin comes with a shortcode to display popular products on any page on your site (other than the catalog page). The shortcode is:

`[upcp-popular-products catalogue_id="123" catalogue_url="https://www.your-site.com/catalog-page/" product_count="4"]`

## Attributes

The upcp-popular-products shortcode takes the following attributes:

`catalogue_id` This attribute is used to select which catalog to show products from. You can find the ID for a catalog by going to the **Catalogs** page. The ID will show in the last column of the table there.

`catalogue_url` This attribute is required and makes it so that, when someone clicks on a product, they are correctly brought to the product page. Input the URL of the page on which you have placed the **Display Product Catalog** block or the **product-catalog** shortcode.

`product_count` This attribute is used to set the number of products you want to show. The default is 3.