---
layout: default
slug: order-tracking
menu: user
title: Zendesk Settings
---
The Order Tracking plugin comes with a Zendesk integration feature that automatically takes any new tickets that you get via Zendesk and creates a corresponding order in the plugin. To enable this, go to **Settings > Zendesk** and toggle on the switch for **Zendesk Integration**.

![Screenshot of Zendesk integration](/img/{{ page.slug }}/otp-zendesk-1.png)

To make sure fake tickets can't be created by a third party, you should also provide your Zendesk API Key.

## Linking Your Zendesk Account

After enabling Zendesk integration in the plugin settings, log in to your Zendesk **Admin** settings area, click on the **Extensions** menu item and then click the **add target** link.

![Screenshot of Zendesk integration](/img/{{ page.slug }}/otp-zendesk-2.png)

Select the **HTTP target** option from the list of available options. Enter a title (ex. Status Tracking ticket created), leave the method as **GET** and the **Basic Authentication** box unchecked. Next, for the URL enter the following:

`http://example.com?Action=Zendesk_Order_Created`

Be sure to replace example.com with the URL of your website. Next, change the dropdown box from **Test Target** to **Create Target** and click the **Submit** button.

Go back to the **Extensions** menu item and then click the **add target** link again. Select the **HTTP target** option from the list of available options. Enter a title (ex. Status Tracking ticket updated), leave the method as **GET** and the **Basic Authentication** box unchecked. Next, for the URL enter the following:

`http://example.com?Action=Zendesk_Order_Updated`

Be sure to replace example.com with the URL of your website. Next, change the dropdown box from **Test Target** to **Create Target** and click the **Submit** button.

Next, click on the **Triggers** menu item, and then click the **Add trigger** button.

![Screenshot of Zendesk integration](/img/{{ page.slug }}/otp-zendesk-3.png)

Now create a trigger that fires when a ticket is created, using these settings.

![Screenshot of Zendesk integration](/img/{{ page.slug }}/otp-zendesk-4.png)

![Screenshot of Zendesk integration](/img/{{ page.slug }}/otp-zendesk-5.png)

Then create another trigger that will fire when a ticket is updated, with these settings.

![Screenshot of Zendesk integration](/img/{{ page.slug }}/otp-zendesk-6.png)

![Screenshot of Zendesk integration](/img/{{ page.slug }}/otp-zendesk-7.png)

That's it!

There should now be an order created each time a ticket is submitted to you via Zendesk, and the status of that ticket should automatically update on your website tracking form each time you update the status of the ticket via Zendesk.