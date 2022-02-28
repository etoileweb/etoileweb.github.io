---
layout: default
slug: ultimate-faq
menu: user
title: ultimate-faq-search Shortcode
---
If you're using the premium version of the plugin, then you can use the following shortcode to create an FAQ search page:

`[ultimate-faq-search]`

## Attributes

This shortcode takes the following attributes:

`show_on_load` Settings this to "Yes" will make it so that your FAQs display on page load. Otherwise only the search field will display.

`post_count` The number of FAQs to display. Don't use this attribute if you want to display them all.

`include_category` Specify which categories you want to include. It will only display FAQs from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`exclude_category` Specify which categories you want to exclude. It will display all FAQs except those from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`display_all_answers` Settings this to "yes" will make it so that, if you are using the FAQ Toggle feature, all FAQs start toggled open. *Please note that this cannot be used with the FAQ Accordion feature as that is designed to display only FAQ at a time.*

`orderby` This attribute is used to specify the sort order of the FAQs when the page loads. Available options are: *title*, *date*, *popular* or *rating*

`order` This attribute is used to set whether you want the sort order (for the option chosen using the **orderby** attribute) to be ascending or descending. Accepted values are: *ASC* or *DESC*

`no_comments` Setting this to "yes" will disable comments for the FAQs.

Example:

`[ultimate-faq-search show_on_load="Yes" include_category="giraffes,elephants" exclude_category="dogs,cats" orderby="name" order="ASC" no_comments="yes"]`
