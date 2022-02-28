---
layout: default
slug: ultimate-reviews
menu: user
title: submit-review Shortcode
---
You can add a submit review form to a page using the following shortcode:

`[submit-review]`

To use this shortcode on the page edit screen, just click the + button and add a new shortcode block to the page. Then write or paste in the above shortcode.

![Gif of adding the shortcode](/img/{{ page.slug }}/urp-add-submit-review-shortcode.gif)

## Attributes

The submit-review shortcode takes the following attributes:

`redirect_page` The URL of the page to which you would like the user redirected after submitting the form.

`product_name` Specify the name of the product you want the review submission to be for. If not used, it will allow the user to specify/choose which product they are leaving the review.

`submit_review_toggle` Setting this to "Yes" will hide the form and display a link that, when clicked, will reveal the form.

`success_message` The message to display after the form is submitted (if not using the redirect_page attribute).

`draft_message` The message to display after the form is submitted if admin approval is required (if not using the redirect_page attribute).

`review_form_title` The title of the form.

`review_instructions` The instruction text displayed below the form title.

`submit_text` The text of the submit button.

Example:

`[submit-review redirect_page="https://www.my-site.com/page/" submit_review_toggle="Yes" product_name="Bicycle" review_form_title="Submit a Review" review_instructions="Please use this form to submit a review" submit_text="Submit"]`
