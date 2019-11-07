# [\a mi.ni.ma\]
"_a simple Low Tech Blog theme for Textpattern CMS_"

This theme tries to have less technological environment impacts: it uses a main dark color to reduice electric consomation on screens, no custom fonts but system ones instead, no social networks links, a recommandation to convert images to half tone versions (image files weight reduiced by half, never mind the formats), with native multilingual features without the help of plugins, Flexbox inside but with fallback for a pretty good cross-browsers support: Internet Explorer 7 minimum.

## How to install?

Place this theme folder and its content into your `root/theme` repertory. Access to your Textpattern's administration interface, then choose the "Themes" panel, import the theme by selecting it into the list, finaly activate it.

## How to use the multilingual feature?

Create sections with a **2 lowercase letters** as name for country codes and asign each to the `default` page template. Choose your main language by setting the page `On default page` (only one alowed). Publish some articles for each sections in the corresponding language.

## How to add other pages (displayed into the sub-menu)?

Create all sections needed by assigning the `default` page template. Check the "Form" panel: you can find the `main_menu_en` (2 letters suffix) as a model. Adapt the `exclude` attribute into the `section_list` tag in order to remove the non corresponding sections for the current language.

**You have to create a "fake" article for each pages with the 2 letters country code for body text in order to identify the language**. Set the status to `persistant`. Now, you can write an article for the page with a published status.

## How to add archive pages?

Create the sections needed and assign its to the `archives` page template. Then process as explain above in order to affect the articles to the pages.

## Configure the theme

Check the `config` form to change the TXP variable according to your needs.

## Theme files

All page templates and forms are provided in compact versions but into more human readable copies. 

## Images convertion

You can use this free online service to convert your images in "Half Tone": http://www.picturetopeople.org/image_effects/photo-halftone/halftone-image-generator.html
