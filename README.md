# Custom Shopify Sections
### Power-ups to supercharge your sales

I created several custom sections to enhance my Shopify stores. So I decided to keep a codebase here. But you can use it if you want.

## To use

1. In Shopify, create 4 files: `flickity.css`, `flickity.pkgd.min.js`, `custom.css`, and `mobile.css` under the `Assets` folder in Shopify.

> Optionally, you can create a 5th file: `newfonts.css` if you want to add custom fonts using `@font-face`.

2. In our repository, go to the `css` folder.
3. Copy each code there (`flickity.css`, etc) and paste into Shopify. e.g: `assets/flickity.css`, etc.
4. In our repository, in the root folder look for `flickity.pkgd.min.js`. Copy the code there and paste into Shopify. e.g.: `assets/flickity.pkgd.min.js`

## After that...

It's time to add your liquid sections. Here's how to do it:

1. In Shopify's code editor, create a new liquid file in your Shopify code editor. Go into the `Sections` folder and create a new section.

2. Name the section the same name from our `sections` folder (e.g. `gallery-tabs`). Make sure you choose `liquid` as the file type.

3. Copy and paste the code in our liquid file to your new liquid file in Shopify (e.g. `sections/gallery-tabs.liquid`)

4. Repeat the last 3 steps for all the liquid files (aka sections) you want to add. I'll describe what each liquid file does later on.

5. The file `assets/Line.png` for `benefits-slider.liquid`. The file `assets/5-stars.svg` is for both `flickity-ugc-slider.liquid` and `reviews-header.liquid`. Upload both files from the `assets` folder into the `Files` section in Shopify to use them.

6. The file `multicolumn.liquid`, simply follow the directions in that file. 3 assets are also added for that file: `warranty.svg`, `guarantee.svg`, and `support.svg`. Add these files to your Shopify `Files` section add them as images in your multicolumn section.

7. The file `assets/right-button-arrow.png` is for the button url at `video-banner.liquid`. Upload the file on Shopify to use it.

> Also: For `video.liquid`, the files are already in Shopify. Simply copy and paste our code to replace the Shopify code already there.

## How to use these custom sections

Simply access the new sections using your theme editor, located in your `Customizer` in Shopify. Add a new section like you would normally add any other section in Shopify...

> To properly use them, get the setting for each slider under the `settings` folder here.

And you're good to go!

## Final note

I tested these new liquid sections using the free `Dawn` theme in Shopify. I'm not sure if they are compatible with any other free Shopify theme. 

You can always test it out to find out.

~ Victor