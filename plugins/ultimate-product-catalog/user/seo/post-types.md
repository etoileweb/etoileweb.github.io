---
layout: default
slug: ultimate-product-catalog
menu: user
title: Post Type Archives
---
Both the products and the catalogs make use of custom post types. As such, when you create a new product or catalog, you are creating a post, and WordPress will automatically assign it a permalink (single post page URL). 

The product pages in our plugin do not make use of this permalink URL assigned by WordPress. Instead, a custom page is used, which allows for the use of all the layouts and options that come with the plugin. 

With this in mind, if, for SEO reasons, you would like to not have the post type URLs crawled by search engines, we suggest using your robots.txt file to disallow them or using a plugin that does it for you. WP Beginner has [a good article](https://www.wpbeginner.com/wp-tutorials/how-to-optimize-your-wordpress-robots-txt-for-seo/) about this.

## Post Type Slugs

For reference, the following are the slugs of the registered post types and taxonomies in the plugin:

The product post type: `upcp_product`

The catalog post type: `upcp_catalog`

The category taxonomy: `upcp-product-category`

The tag taxonomy: `upcp-product-tag`