---
layout: default
slug: ultimate-faq
menu: user
title: Frequently Asked Questions
---
Quick answers to your most common questions. Anything missing? [Let us know](https://www.etoilewebdesign.com/support-center/).

## <a name="shortcode"></a>Is there a shortcode to display FAQs?

Yes, you can use the `[ultimate-faqs]` shortcode. For more info, see [here](blocks-shortcodes/ultimate-faqs-shortcode).

## <a name="block"></a>Is there a Gutenberg block to display FAQs?

Yes, you can search for the **Display FAQs** block. Alternatively, you'll find it in its own block category/section called **Ultimate FAQs**. For more info, see [here](blocks-shortcodes/display-faqs-block).

## <a name="multiple-faq-pages"></a>Can I have multiple FAQ pages with different FAQs on each?

Yes. For this, we would recommend assigning your FAQs to different categories and then using the shortcode to include only the category you want on each page. For more info, see [here](blocks-shortcodes/ultimate-faqs-shortcode).

## <a name="sort-order"></a>How do I sort the order of my FAQs?

The FAQs can be sorted by title, created date or modified date. The FAQ categories can be sorted by name, slug or count. If you are using the premium version, there is also a drag-and-drop table that can be used for precise ordering. For more info, see [here](faqs/order).

## <a name="translate"></a>Can I translate my FAQs?

Yes, the plugin uses a custom post type and all the strings/labels are localized in the code. For more information on plugin translation, please see [here](labelling/translating).

## <a name="wpml"></a>Is this compatible with WPML?

Yes, the plugin uses a custom post type and taxonomies. As such, if you enable our post type in the WPML settings, you'll be able to create translations of your FAQs, categories and tags. As well, all the strings/labels are localized in the code. As such, they will be picked up by WPML's String Translation tool for easy direct translating. 

For more info on translating the plugin, please see [here](labelling/translating).

## <a name="custom-fields"></a>Can I add extra fields to my FAQs?

Yes, the premium version of the plugin includes the **Fields** feature, which lets you add custom fields to your FAQs. For more info, see [here](custom-fields).

## <a name="single-ufaq"></a>The individual FAQ page isn't displaying correctly

For the FAQ single post pages, it would be your theme that controls the look and layout. Because the FAQs are a custom post type, the single post page for FAQ posts would, by default, make use of your theme's single.php template file. If you'd like to modify the single post page for FAQs, we'd suggest duplicating your single.php file and creating one specifically for our post type, as discussed [here](https://codex.wordpress.org/Post_Type_Templates). Our post type is called **ufaq**, so you'd want to call your template file **single-ufaq.php**.

## <a name="trial"></a> Do you offer a free trial of the premium version?

Yes, we do! For info on how to activate the free trial, please see [here](premium/trial).

## <a name="support"></a> How do I contact support?

For more info on contacting support, please see [here](support/contact).

{% include faq/refund.md %}