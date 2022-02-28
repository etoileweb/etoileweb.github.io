---
layout: default
slug: ultimate-product-catalog
menu: user
title: insert-products Shortcode
---
The plugin comes with a separate shortcode that lets you insert products on any page on your site (other than the catalog page). This is useful if, for example, you'd like to include some featured products on your homepage. The shortcode is:

`[insert-products catalogue_url="https://www.your-site.com/catalog-page/" product_count="4" catalogue_id="123"]`

## Attributes

The insert-products shortcode takes the following attributes:

`catalogue_url` This attribute is required and makes it so that, when someone clicks on a product, they are correctly brought to the product page. Input the URL of the page on which you have placed the Display Product Catalog block or the product-catalog shortcode.

`product_count` This attribute is used to set the number of products you want to show. The default is 3 (so, if you want 3, you do not need to use this attribute).

*One of the following four attributes is also required, to correctly populate the shortcode:*

`catalogue_id` This attribute is used to select which catalog to show products from. You can find the ID for a catalog by going to the **Catalogs** page. The ID will show in the last column of the table there.

`category_id` This attribute is used to show products from specific categories. Takes the category ID. To find the ID of a category, go to the **Categories** page and click on the category. The ID will show in your browser's address bar.

`subcategory_id` This attribute is used to show products from specific sub-categories. Takes the sub-category ID. To find the ID of a sub-category, go to the **Categories** page and click on the sub-category. The ID will show in your browser's address bar.

`product_ids` This attribute is used to specify which individual products you want to show. Takes a comma-separated list of product IDs. To find the ID of a product, go to the **Products** page. The ID will show in the **Post ID** column (last column) of the table there. For example:

`[insert-products catalogue_url="https://www.your-site.com/catalog-page/" product_ids="123,124,125"]`