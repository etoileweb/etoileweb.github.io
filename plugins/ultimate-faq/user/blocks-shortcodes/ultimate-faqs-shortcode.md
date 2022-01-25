---
layout: default
slug: ultimate-faq
menu: user
title: ultimate-faqs Shortcode
---
You can add your FAQs to a page using the following shortcode:

`[ultimate-faqs]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

![Gif of adding the shortcode](/img/{{ page.slug }}/ufaq-add-ultimate-faqs-shortcode.gif)

## Attributes

The ultimate-faqs shortcode takes the following attributes:

`post_count` The number of FAQs to display. Don't use this attribute if you want to display them all.

`include_category` Specify which categories you want to include. It will only display FAQs from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`exclude_category` Specify which categories you want to exclude. It will display all FAQs except those from these categories. Takes a comma-separated list of category slugs. e.g.: *my-first-category,my-second-category*

`include_category_ids` Specify which categories you want to include by ID. It will only display FAQs from these categories. Takes a comma-separated list of category IDs.

`exclude_category_ids` Specify which categories you want to exclude by ID. It will display all FAQs except those from these categories. Takes a comma-separated list of category slugs.

`include_tag` Specify which tags you want to include. It will only display FAQs from these tags. Takes a comma-separated list of tag slugs. e.g.: *my-first-tag,my-second-tag*

`include_category_children` If using the include_category attribute, then setting this to "yes" will include sub-categories in the displayed FAQs as well. *Please note that, if you have the same FAQs in multiple sub-categories, this could mean they will display more than once on your FAQ page.*

`display_all_answers` Settings this to "yes" will make it so that, if you are using the FAQ Toggle feature, all FAQs start toggled open. *Please note that this cannot be used with the FAQ Accordion feature as that is designed to display only FAQ at a time.*

`orderby` This attribute is used to specify the sort order of the FAQs when the page loads. Available options are: *title*, *date*, *popular* or *rating*

`order` This attribute is used to set whether you want the sort order (for the option chosen using the **orderby** attribute) to be ascending or descending. Accepted values are: *ASC* or *DESC*

`no_comments` Setting this to "yes" will disable comments for the FAQs.

Example:

`[ultimate-faqs post_count="20" include_category="giraffes,elephants" exclude_category_ids="34,68" display_all_answers="yes" orderby="name" order="ASC" no_comments="yes"]`
