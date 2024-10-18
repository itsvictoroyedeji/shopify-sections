# Custom Shopify Sections

I created several custom sections for Shopify. So I kept them here.

## To use

Create 2 files: `flickity.css` and `flickity.pkgd.min.js` under the `Assets` folder in Shopify. Then copy the code I have (from the same filenames) and paste into Shopify. e.g: `assets/flickty.css` `assets/flickity.pkgd.min.js`

Copy the `base.css` file and paste it to the bottom of your `assets/base.css` file in Shopify. 

Then create a `mobile.css` file under `Assets` in Shopify and copy/paste my `mobile.css` code to your new assets/mobile.css file in Shopify.

## After that:

- Create a new liquid file in your Shopify code editor under `Sections` using the same name (e.g. `benefits-slider`). Make sure you choose `liquid` as the file type.

- Copy and paste the code in my liquid file to your new liquid file in Shopify (e.g. `sections/benefit-slider.liquid`) 

- Repeat the same steps for the rest of the liquid files.

```
For `video.liquid`, the files are already in Shopify. Simply copy and paste my code to replace the Shopify code already there.
```

## How to use

Access the new sections using your theme editor, located in your `Customizer` in Shopify. Simply add a new section and look for the new sections towards the bottom.

And you're good to go!

## Final note

I tested these new liquid sections using the free `Dawn` theme in Shopify. I'm not sure if they are compatible with other free Shopify themes. But you can always test it out to find out.
