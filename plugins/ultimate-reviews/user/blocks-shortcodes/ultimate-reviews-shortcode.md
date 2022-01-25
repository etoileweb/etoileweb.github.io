---
layout: default
slug: ultimate-reviews
menu: user
title: ultimate-reviews Shortcode
---
You can add your reviews to a page using the following shortcode:

`[ultimate-reviews]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

![Gif of adding the shortcode](/img/{{ page.slug }}/urp-add-ultimate-reviews-shortcode.gif)

## Attributes

The ultimate-reviews shortcode takes the following attributes:

`post_count` The number of reviews to display. Don't use this attribute if you want to display them all.

`product_name` Specify the name of the product for which you want to show reviews. If not used, it will show reviews for all products.

`review_author` Specify which author's reviews you would like to show.

`reviews_per_page` Specify how many reviews you would like to show per page.

`min_score` Specify the minimum score/rating of review to show.

`max_score` Specify the maximum score/rating of review to show.

`group_by_product` Set to "Yes" if you would like to group the reviews by product.

`include_category` Specify which categories you want to include. It will only display reviews from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`exclude_category` Specify which categories you want to exclude. It will display all reviews except those from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`include_category_ids` Specify which categories you want to include by ID. It will only display reviews from these categories. Takes a comma-separated list of category IDs.

`exclude_category_ids` Specify which categories you want to exclude by ID. It will display all reviews except those from these categories. Takes a comma-separated list of category IDs.

`include_ids` Choose specific reviews to show. It will only display these reviews. Takes a comma-separated list of review IDs. e.g.: *123,223,323*

`exclude_ids` Choose specific reviews to not show. It will display all reviews except these. Takes a comma-separated list of review ID. e.g.: *123,223,323*

`orderby` This attribute is used to specify the sort order of the reviews when the page loads. Available options are: *ewd_urp_views*, *ewd_urp_product*, *ewd_urp_score* or *ewd_urp_flagged*

`order` This attribute is used to set whether you want the sort order (for the option chosen using the **orderby** attribute) to be ascending or descending. Accepted values are: *ASC* or *DESC*

Example:

`[ultimate-reviews post_count="20" reviews_per_page="5" min_score="2" max_score="5" include_category="giraffes,elephants" exclude_category_ids="34,68" orderby="name" order="ASC" no_comments="yes"]`
