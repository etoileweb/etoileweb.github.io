---
layout: default
slug: ultimate-reviews
menu: user
title: Frequently Asked Questions
---
Quick answers to your most common questions. Anything missing? [Let us know](https://www.etoilewebdesign.com/support-center/).

## <a name="submit-shortcode"></a>Is there a shortcode to display the submit review form?

Yes, you can use the `[submit-review]` shortcode. For more info, see [here](blocks-shortcodes/submit-review-shortcode).

## <a name="display-shortcode"></a>Is there a shortcode to display reviews?

Yes, you can use the `[ultimate-reviews]` shortcode. For more info, see [here](blocks-shortcodes/ultimate-reviews-shortcode).

## <a name="submit-block"></a>Is there a Gutenberg block to display the submit review form?

Yes, you can search for the **Submit Review** block. Alternatively, you'll find it in its own block category/section called **Ultimate Reviews**. For more info, see [here](blocks-shortcodes/submit-review-block).

## <a name="display-block"></a>Is there a Gutenberg block to display reviews?

Yes, you can search for the **Display Reviews** block. Alternatively, you'll find it in its own block category/section called **Ultimate Reviews**. For more info, see [here](blocks-shortcodes/display-reviews-block).

## <a name="multiple-review-pages"></a>Can I have multiple reviews pages with different reviews on each?

Yes. For this, you can the shortcode to include reviews for only one specific product or from only one specific category. So, you could, for example, assign all the reviews that you want to show on a specific page to a category and then use the shortcode to display only reviews from that category. For more info, see [here](blocks-shortcodes/ultimate-reviews-shortcode).

## <a name="sort-order"></a>How do I sort the order of my reviews?

The reviews can be sorted by title, submitted date, rating or karma. For more info, see [here](reviews/order).

## <a name="custom-fields"></a>Can I add extra fields to my reviews/submit review form?

Yes, you just need to enable the in-depth reviews feature and then create the fields you want. For more info, see [here](custom-fields).

## <a name="in-depth-reviews"></a>How do I add multiple rating categories to my submit review form?

To do this, you need to enable in-depth reviews and then create *Review Line* type fields. For more info, see [here](custom-fields/create).

## <a name="single-urp"></a>The review single post page isn't displaying correctly

For the review single post pages, it would be your theme that controls the look and layout. Because the reviews are a custom post type, the single post page for review posts would, by default, make use of your theme's single.php template file. If you'd like to modify the single post page for reviews, we'd suggest duplicating your single.php file and creating one specifically for our post type, as discussed [here](https://codex.wordpress.org/Post_Type_Templates). Our post type is called **urp_review**, so you'd want to call your template file **single-urp_review.php**.

## <a name="translate"></a>Can I translate my reviews?

Yes, the plugin uses a custom post type and all the strings/labels are localized in the code. For more information on plugin translation, please see [here](labelling/translating).

## <a name="wpml"></a>Is this compatible with WPML?

Yes, the plugin uses a custom post type and taxonomies. As such, if you enable our post type in the WPML settings, you'll be able to create translations of your reviews and categories. As well, all the strings/labels are localized in the code. As such, they will be picked up by WPML's String Translation tool for easy direct translating. 

For more info on translating the plugin, please see [here](labelling/translating).

## <a name="trial"></a> Do you offer a free trial of the premium version?

Yes, we do! For info on how to activate the free trial, please see [here](premium/trial).

## <a name="support"></a> How do I contact support?

For more info on contacting support, please see [here](support/contact).

{% include faq/refund.md %}