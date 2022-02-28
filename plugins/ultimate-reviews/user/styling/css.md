---
layout: default
slug: ultimate-reviews
menu: user
title: Custom CSS
---
In certain cases, you may not be able to achieve exactly what you want using only the styling options. To further customize the look and layout of your reviews, you can add some of your own CSS.

We've added a **Custom CSS** input area to the top of the **Basic** settings page, which you can use to add your custom CSS. If you'd prefer, you can also/instead use the Additional CSS area in your theme's customizer for this. 

*Please note that using custom CSS to modify the look of your reviews requires knowledge of CSS. Attempting to modify your reviews without this knowledge may result in messing up the layout and even possibly altering/removing certain functionality.*

As an example, let's say that you wanted to make the font size bigger and the color green for the review title. The following CSS would help you to achieve that:

`.ewd-urp-review-title {
  font-size: 24px;
  color: green;
}`

![Gif of adding custom CSS](/img/{{ page.slug }}/urp-custom-css.gif)

## CSS Selectors

Some common CSS selectors from the plugin are:

`.ewd-urp-reviews` Main overall container for the display reviews shortcode/block output

`.ewd-urp-summary-statistics-div` Container for the summary statistics area

`.ewd-urp-standard-summary-graphic-sub-group` The background of a summary statistic bar

`.ewd-urp-standard-summary-graphic-full-sub-group` The fill part of a summary statistic bar

`.ewd-urp-review-div` Container for an individual review

`.ewd-urp-review-score` Review score area (stars and number rating)

`.ewd-urp-review-title` Review title

`.ewd-urp-author-date-categories` Container for the area that shows the review author, date and associated categories.

`.ewd-urp-review-body` Main review body text

`.ewd-urp-category-field` Container for an in-depth review field

`.ewd-urp-category-score-label` In-depth field label

`.ewd-urp-category-score-number` In-depth field value

`.ewd-urp-review-format-thumbnail` Thumbnail format review container

`.ewd-urp-review-format-expandable` Expandable format review container

`.ewd-urp-review-format-image` Image format review container

`.ewd-urp-review-image` Review image (in Image format)

`.ewd-urp-review-format-image .ewd-urp-review-score, .ewd-urp-review-format-image_masonry .ewd-urp-review-score` Score/rating area in Image format

`.ewd-urp-review-form` Main overall container for the submit review form

`.ewd-urp-review-form .form-field` Container for individual field in the submit review form (product name, review author and review title)

`.ewd-urp-review-form .ewd-urp-meta-field` Container for individual field in the submit review form (main review text and any added fields)

`.ewd-urp-review-form label` Submit review form label

`.ewd-urp-stars-input` Star input in submit review form

`.ewd-urp-captcha-response` Captcha input in submit review form

`#ewd-urp-review-submit` Submit review button