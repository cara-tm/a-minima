# [\a mi.ni.ma\]
a simple "Low Tech" Blog theme for Textpattern CMS

This theme tries to have less technological environment impacts: it uses a main dark color to reduice electric consomation on screens, no custom fonts but system ones instead, no social networks links, a recommandation to convert images to half tone versions (image files weight reduiced by 2 never mind the formats), with native multilingual features without the help of plugins, Flexbox inside but with fallback for a pretty good browsers support: Internet Explorer 7 minimum.

## How to instal?

Place this theme folder and its content into your `root/theme` repertory. Access to your Textpattern administration interface, then choose the "Themes" panel, import the theme by selecting it into the list, finaly activate it.

## How to use the multilingual feature?

Create sections with a 2 letters name for country codes and asign each to the `default` page template. Choose your main language by setting the page "on front". Publish some articles for each sections in the corresponding language.

## How to add other pages?

Create all sections needed by assigning the `default` page template. Check the "Form" panel: you can find the main_menu_en as a model. Adapt the exclude attribute in order to remove the non corresponding section for the language (2 letters suffix).

You have to create a "fake" article for each pages with the 2 letters country code for body text. Set the status to `persistant`. Now, you can write an article for the page with a published status.

## Configure the theme

Check the `config` form to change the TXP variable according to your needs.
