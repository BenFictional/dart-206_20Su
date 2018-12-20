You may have already created some original graphics for your narrative site while preparing the mockup, but this exercise will ensure that students are capable of creating web-optimized graphics and utilizing them in development.

### Objectives

* Design original artwork or graphics for use in your website
* Export files optimized for the web
* Set a favicon and touch icon for your site \(32x32 and 256x256 PNG files\)

### Requirements

* Design a vector icon or illustration in Adobe Illustrator.
* Include the vector graphic in your website.
* Set a graphic as a favicon for your site in Webflow.
* Do **not** use a photograph as your favicon. 

You can use the same image for inclusion in your site and the favicon, or you can make two different vector images if your idea for a favicon doesn't make sense to include in the actual content of your site.

### What's a favicon?

A [favicon](https://en.wikipedia.org/wiki/Favicon) is the small graphic displayed in the tab of web browsers, and while it is frequently a personal or corporate logo, it can be any image you like—especially for art websites like the one's we're making in this unit.

Favicons were originally designed to be shown in the bookmarks menu of Internet Explorer in 1999, showing a users' "favorite" sites. Originally favicons had to be 16px x 16px images located in a site's root folder, and they had to be called "favicon.ico" using an obscure file format.

Today most favicons are 32px x 32px PNG images, and they don't have to be stored in the root folder. Many sites also include larger "Touch-icons" for use in certain contexts on mobile devices.

Webflow makes it very easy to set a favicon for your site, but if you ever want to set up a favicon in another development platform, here is a [thorough guide for all your icon needs.](https://css-tricks.com/favicon-quiz/)

![](/assets/lesson-4/top-favicons.jpg)

This image shows the favicons of the top 300,000 websites, with their size determined by their relative page-views. You can browse also see an [interactive version of the visualization](https://nmap.org/favicon/), which really shows the popularity of red and blue. Why do you think that is?

### Workflow

While your finished favicon should be 32px x 32px, it will be much easier to design it at a larger size, and then resize it when you're finished. Designing your icons in Illustrator will provide the most flexibility because vector artwork can be infinitely resized without any change in quality.

1. Create a new document that is 256px x 256px \(or larger, as long as it's square\). 
2. Design your icon and place it within your artboard. 
4. File » Export » Export for screens
6. Select the export format:
   1. PNG
   2. Click on "Scale" and change it from "1x" to "32px".
   3. Click the "Add scale" button and set the second row to "256px".
7. Click Export

**Set your favicon in Webflow:**

This is pretty easy, just go to your site's Settings page and scroll down on the General tab. Read full instructions here about [setting your favicon and touch icon](https://university.webflow.com/article/favicons-and-touch-icons).

Upload both your 32px and 256px icons and see how they look in the browser... is the graphic legible in the tab bar? Should it have a transparent background? 

### Design Tips

Consider how your icon will look when it is very small... you can easily zoom out a bunch in Illustrator to get an idea of how it will look. Many designers will create different versions of a logo for use at small scales.

![](/assets/lesson-4/Adapting-Logos.png)

In these examples, the brand logos begin as [combination marks](https://99designs.com/blog/tips/types-of-logos/) \(text+image\), but offer enough flexibility to create several different versions. The simplest versions are minimal icons that would work well as favicons.

![](/assets/lesson-4/argento-logo.png)In this example the changes to the logo are very subtle, but help with legibility at small scales.

For this exercise, you might make a traditional logo, but you could also make a more illustrative drawing. It will depend on the content of your site.

When designing your artwork, consider where you want to put the image in your website in addition to the favicon. If you export the image as an SVG you can display it at any size, but a PNG will look pixelated if you create it at 320px wide but set it to occupy a 1000px wide space in Muse.

### Submission

Submit the following to Canvas:

* Exported PNG image of your vector artwork; must be full-size \(i.e. larger than 32px x 32px\).
* Screenshot showing your favicon and touch icon in the Webflow project settings page. 

\[INSERT SUBMISISON LINK\]

