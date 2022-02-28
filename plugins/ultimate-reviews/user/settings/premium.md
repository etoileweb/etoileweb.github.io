---
layout: default
slug: ultimate-reviews
menu: user
title: Premium Settings
---
The following options are available by going to **Settings > Premium**

### Review Format

Select which display style/layout/format you would like to use on your reviews page.

### Captcha

Should a captcha be added to the submit review form to prevent spamming?

### Captcha Type

Options are plain text captcha and Google's reCAPTCHA. Plain text requires image-creation support be enabled in your PHP installation. Plain text will also soon be deprecated as it is easier to bypass. See [here](https://www.etoilewebdesign.com/2021/09/02/setting-up-recatpcha-in-the-ultimate-reviews-plugin/) for more information on how to configure Google reCAPTCHA.

### Review Karma

Should visitors be allowed to vote up or down on reviews that they find or don't find useful? (i.e. "Did you find this review helpful?") Uses cookies to make it more difficult to vote up or down multiple times.

### Infinite Scroll

If there are more than the maximum number of reviews per page displayed, should the next page of reviews be loaded automatically by AJAX, so that the page doesn't need to be reloaded? This may not work if you also have a review widget displaying on the same page.

### Include Microdata

Should schema structured be added to the reviews when they're displayed? This helps search engines to display your reviews in a more helpful format.

### Items Reviewed

For microdata to work correctly, the type of items being reviewed needs to be specified.

### Admin Notification Email

Should an email be sent to the WordPress admin?

### Summary Statistics

Should a summary of the reviews be displayed at the top (average score, etc.)? This feature may not work as expected with in-depth reviews and/or pagination.

### Clickable Summary Stats

Should visitors be able to click on the summary statistic bars to view all reviews with that score?

### Thumbnail Characters

What is the maximum number of characters that should be shown in the preview in thumbnail format?

### Thumbnail *Read More* AJAX

If you have selected the *Thumbnail* format, should the content be loaded on the same page when clicking *Read More*?

### Require Admin Approval

Should new reviews have their status set to *draft* until an admin decides to publish them? See [here](../reviews/approve) for more info.

### Require Author Email

Do reviewers have to include their email address (not publicly displayed) when they post a review?

### Display Form on Confirmation

Should the submit review form be displayed when someone is confirming their email address?

### One Review per Person/Product

Should users be restricted to leaving one review per product? Uses cookies to track which products a user has reviewed.

### Review Blacklist

Enter terms, one per line, that should block reviews from being submitted. This can include IP addresses that you want to block, review titles, author names, email addresses, etc.

### Require Login

Do reviewers have to log in before they can post a review?