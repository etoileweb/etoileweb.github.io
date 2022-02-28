---
layout: default
slug: ultimate-faq
menu: developer
plugin_title: Ultimate FAQ
title: Ultimate FAQ Developer Documentation
---
The developer documentation is for coders who want to learn how to modify or extend the plugin with the available template system<!--, filters and hooks-->.

*If you're not a coder, you're probably looking for the [User Guide](../user).*

## Templates

Starting with version 2.0.0 of {{ page.plugin_title }}, everything that displays on the front end of the plugin can be customized by creating your own template files (to modify and/or overwrite the existing templates files), which can be done as per the following: 

1. To get started, you should have FTP access to your server (in the screenshots below, we’re using FileZilla), so that you can download and upload files to your WordPress installation. Navigate to the templates folder for the plugin that you’re editing. For {{ page.plugin_title }}, you would click on **wp-content** > **plugins** > **ultimate-faqs** > **ewd-ufaq-templates**.

2. Next, find the template that you want to edit. In our case, we’re going to change the FAQ answer to add the label **Answer:** before each FAQ answer, so we’ll download the **faq-answer** template to our desktop.

    ![Screenshot of FileZilla FTP](/img/{{ page.slug }}/ufaq-developer-templates-1.png)

3. Open up the file that you downloaded. You should see the HTML div that contains the structure, along with where the answer is being added. We’ll add in our label before the answer text, and then save that file.

    ![Screenshot of modified template code](/img/{{ page.slug }}/ufaq-developer-templates-2.png)

4. Now we need to add that file to our server. Navigate to the child theme you’re using, or your active theme if you’re not using a child theme, and create a folder with the same name as the templates folder in the plugin, so **ewd-ufaq-templates** in our case.

5. Upload the file you edited to that folder. The plugin will automatically use any templates with the same names found in your active theme’s folder. Once you’ve done that, you should see a label before each of your FAQs.

    ![Screenshot of modified FAQ page output](/img/{{ page.slug }}/ufaq-developer-templates-3.png)

That’s all it takes to edit or change any of the content displayed on the front end by {{ page.plugin_title }}!