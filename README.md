# [\a mi.ni.ma\\]
"_a simple Low Tech Blog theme for Textpattern CMS_"

This theme tries to have less technological environmental impacts: it uses a main dark color to reduce electric consumption on screens, no custom fonts but system ones instead, no social networks links, a recommendation to convert images to half tone versions (image files weight reduced by half, never mind the formats), with native multilingual features without the help of plugins, Flexbox inside but with fallback for a pretty good cross-browser support: Internet Explorer 7 minimum.

## How to install?

Place this theme folder and its content into your `root/theme` repertory. Access to your Textpattern's administration interface, then choose the "Themes" panel, import the theme by selecting it into the list, finally activate it.

**Important note**: After installation, you'll can visit your public home page but you'll encourt errors messages for individual article display context. **It's normal**: due to multilingual feature, [\a mi.ni.ma\\] need a _special_ section (this one is the minimum required) to work (_even if you do not want to create a multilingual website_). Start to create an `en` section attached to the `default` page template and set it "On front page" (or rename the `articles` one), then associate your first article (or the default one shiped with the Textpattern distribution) to it. 

## How to use the multilingual feature?

Create sections with a **2 lowercase letters** as name for country codes and assign each to the `default` page template. Choose your main language by setting the page `On default page` (only one allowed). Publish some articles for each section in the corresponding language.

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
