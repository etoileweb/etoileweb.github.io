---
layout: default
slug: ultimate-product-catalog
menu: user
title: product-catalog Shortcode
---
You can add a catalog to your page using the following shortcode:

`[product-catalog id="X"]`

or

`[product-catalogue id="X"]`

Where "X" is the ID of your catalog. You can find the exact shortcode for the catalog you want to display by going to the **Catalogs** page.

![Screenshot of shortcode in Catalogs tab](/img/{{ page.slug }}/upcp-catalogs-tab-shortcode.png)

Copy that shortcode and then, on the page edit screen, just click the + button and add a new shortcode block to the page. Then paste in the shortcode.

![Gif of adding the shortcode](/img/{{ page.slug }}/upcp-add-product-catalog-shortcode.gif)

## Attributes

The product-catalog shortcode takes the following attributes:

`id` This attribute is used to specify the ID of the catalog you want to display. You can find the ID for a catalog by going to the **Catalogs** page, as referenced above.

`starting_layout` This attribute is used to select which of the three available catalog layouts (Thumbnail, Detail or List) you want as your starting layout. All three layouts will still show regardless of the selection here. You must capitalize the layout name.

`excluded_layouts` This attribute is used to specify any layouts that you don't want to be included on your catalog page. You must capitalize the layout name and comma-separate each entry. For example: *Thumbnail,List*

`sidebar` This attribute is used to select whether or not you want the filtering sidebar to display on the catalog page. Takes "Yes" or "No" as a value.

`overview_mode` This attribute is used to set which overview mode to use. Takes "Full" or "Categories" as a value. Don't include the attribute if you don't want to use overview mode or have specified your choice in the settings.

`category` This attribute is used to pre-filter the catalog to show only products from one specific category. Takes the category ID. To find the ID of a category, go to the **Categories** page and click on the category. The ID will show in your browser's address bar.

`subcategory` This attribute is used to pre-filter the catalog to show only products from one specific sub-category. Takes the sub-category ID. To find the ID of a sub-category, go to the **Categories** page and click on the sub-category. The ID will show in your browser's address bar.

`tags` This attribute is used to pre-filter the catalog to show only products from one specific tag. Takes the tag ID. To find the ID of a tag, go to the **Tags** page and click on the tag. The ID will show in your browser's address bar. 

`prod_name` This attribute is used to pre-filter the catalog to a specific search term.

`max_price` This attribute is used to pre-filter the catalog to show only prices that are equal to or less than the specified value. 

`min_price` This attribute is used to pre-filter the catalog to show only prices that are equal to or more than the specified value. 

`orderby` This attribute is used to specify the sort order of the catalog when the page loads. Available options are: *name*, *price*, *rating* or *date*

`order` This attribute is used to set whether you want the sort order (for the option chosen using the **orderby** attribute) to be ascending or descending. Accepted values are: *ASC* or *DESC*

`omit_fields` This attribute is used to omit specific fields from the product comparison page. Takes a comma-separated list. The following fields are available: *image,price,categories,subcategories,tags*

`products_per_page` (Premium only) This attribute is used to specify the number of products per page you want to show.

`current_page` (Premium only) This attribute is used to select which page the catalog should load on if you have set a specific number of products per page.

Example using all attributes:

`[product-catalog id="123" starting_layout="Detail" excluded_layouts="Thumbnail,List" sidebar="No" overview_mode="Full" category="2" sub-category="9" tags="14" prod_name="bicycle" max_price="900" min_price="100" orderby="name" order="ASC" omit_fields="categories,tags" products_per_page="10" current_page="2"]`
