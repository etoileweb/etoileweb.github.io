---
layout: default
slug: ultimate-reviews
menu: user
title: reviews-summary Shortcode
---
The plugin comes with the following shortcode to display a summary of your reviews:

`[reviews-summary]`

## Attributes

This shortcode takes the following attributes:

`product_name` Specify the name of the product for which you want to show the summary

`include_category` Specify which categories you want to include. It will only display reviews from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`exclude_category` Specify which categories you want to exclude. It will display all reviews except those from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`summary_type` Specify the type of summary you would like to show. The two options are *full* and *limited*.

Example:

`[reviews-summary product_name="Bicycle" summary_type="full"]`

