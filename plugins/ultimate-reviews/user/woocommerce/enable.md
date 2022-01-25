---
layout: default
slug: ultimate-reviews
menu: user
title: Enable and Set Up WooCommerce Reviews 
---
To enable the WooCommerce integration, go to the **WooCommerce** area of the **Settings** page in the plugin admin.

![Screenshot of WooCommerce settings](/img/{{ page.slug }}/urp-woocommerce-1.png)

Enable the **Replace WooCommerce Reviews** option to make WooCommerce use the Ultimate Reviews system. This will replace the **Reviews** tab found on the product page with the reviews from our plugin. This will include both the display of any existing reviews for that product as well as the submit review form. 

You can choose to display the submit review form above the reviews by enabling the **Submit Review on Top** option.

The **Only Review WooCommerce Products** option is useful if you plan on using the submit review [block](../blocks-shortcodes/submit-review-block) or [shortcode](../blocks-shortcodes/submit-review-shortcode) elsewhere on your site. It makes it so that only WooCommerce products can be reviewed.

There are further options to choose which **WooCommerce Review Types** to show, to **Match WooCommerce Categories**, so the reviews get automatically assigned to the same category as the product, and to **Display Related Reviews** in the event that a specific product has no reviews or less than a specified number of reviews.

### Ratings and Stars

If you enable the **Override Product Page Ratings** option, it will replace the overall rating/score on the product page with one calculated from the reviews in our plugin. This affects both the numerical score and the displayed star rating. 

*It's important to note, however, that, for the stars, your theme must support the WooCommerce rating stars to begin with. Our plugin does not create or add the star graphic itself. It replaces the calculated score used by the star graphic. If your theme doesn't already display the star graphic with WooCommerce's built-in reviews, it will not display it with our reviews.*

![Screenshot of front-end WooCommerce product page](/img/{{ page.slug }}/urp-woocommerce-4.png)

The WooCommerce integration also comes with the ability to send reminders to people who have purchased any/certain products to ask them to review the product(s). You can find more info about this [here](reminders).

