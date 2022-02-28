---
layout: default
slug: ultimate-product-catalog
menu: user
title: Custom CSS
---
In certain cases, you may not be able to achieve exactly what you want using only the styling options. To further customize the look and layout of your catalog, you can add some of your own CSS.

We recommend using the Additional CSS area in your theme's customizer for this.

*Please note that using custom CSS to modify the look of your catalog requires knowledge of CSS. Attempting to modify your catalog without this knowledge may result in messing up the layout and even possibly altering/removing certain functionality.*

As an example, let's say that, on the tabbed product page, you want the image area to take up less space and the tabbed area to take up more. This is easily achievable with a few lines of CSS. For example, the following CSS makes the images div smaller and the tabs div wider:

`.ewd-upcp-single-product-images-div {
  width: 27%;
}`
`.ewd-upcp-single-product-details {
  width: 67%;
}`

![Gif of adding the catalog block](/img/{{ page.slug }}/upcp-custom-css-1.gif)

## CSS Selectors

Some common CSS selectors from the plugin are:

`.ewd-upcp-catalog-sidebar` Main sidebar container

`.ewd-upcp-catalog-sidebar-sort` Sidebar sort by area

`.ewd-upcp-catalog-sidebar-search` Sidebar search area

`.ewd-upcp-catalog-sidebar-price-filter` Sidebar price slider

`.ewd-upcp-catalog-sidebar-categories` Sidebar categories area

`.ewd-upcp-catalog-sidebar-subcategories` Sidebar sub-categories area

`.ewd-upcp-catalog-sidebar-tags` Sidebar tags area

`.ewd-upcp-catalog-sidebar-custom-fields` Sidebar custom fields area

`.ewd-upcp-catalog-sidebar-custom-field-div` Sidebar individual custom field

`.ewd-upcp-catalog-display` Main catalog area container

`.ewd-upcp-catalog-product-thumbnail` Main thumbnail container

`.ewd-upcp-catalog-product-thumbnail-image-div` Thumbnail image

`.ewd-upcp-catalog-product-thumbnail-body-div` Thumbnail body

`.ewd-upcp-list-view` Main list view container

`.ewd-upcp-catalog-product-list` List view product container

`.ewd-upcp-catalog-product-list .ewd-upcp-product-title-div` List view title area

`.ewd-upcp-catalog-product-list .ewd-upcp-catalog-product-price` List view price area

`.ewd-upcp-detail-view` Main detail view container

`.ewd-upcp-catalog-product-detail` Detail view product container

`.ewd-upcp-catalog-product-detail-image-div` Detail view image area

`.ewd-upcp-catalog-product-detail-mid-div` Detail view content area

`.ewd-upcp-catalog-product-detail-end-div` Detail view price area

`.ewd-upcp-product-comparison-button` Comparion button

`.ewd-upcp-sale-price` Sale button

`.ewd-upcp-pagination` Pagination controls

`.pagination-links` Individual pagination button