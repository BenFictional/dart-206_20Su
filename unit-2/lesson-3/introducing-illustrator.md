#Introducing Illustrator

The Adobe Creative Suite is the industry standard for many types of digital media. For designing digital graphics and layouts, there are some other options, but we're going to use the Adobe Suite because it's so widely used and your free subscription also includes Photoshop, which is useful for cropping, resizing, and optimizing raster images for the web.

Before we start developing our next site, we're going to create 2D **mockups** as a means to plan out layouts and graphics elements like icons and backgrounds.

**Adobe Photoshop** is one option for this type of work. As its name implies Photoshop is primarily designed for manipulating photos, but many people use it for creating other graphics. Photoshop is primarily used for creating **raster images**—which means images made of pixels like JPEGs or PNGs. Use Photoshop to resize and compress JPEG files that you want to use on the web to reduce page load time.

**Adobe Illustrator** is also used for creating graphics and 2D designs, but unlike Photoshop it works with **vector images**. Vector images are defined by points and paths and do not rely on pixels \(though vector images can be converted to raster filetypes\). The advantage of vector images is that they can be viewed or printed at any scale without any loss in quality; they also take up _much less_ file space, which is important for web design where loading speed is a major concern. Vector filetypes include SVG, EPS, and PDF.

![raster-vector](/assets/lesson-2/raster-vector.png)

I recommend using Illustrator for web design for a couple reasons:

1. It makes it easier to arrange and resize lots of elements; Photoshop keeps each shape and text object in a separate layer.
2. Its export feature is specifically designed for creating assets for web and app development.
3. The ability to work with multiple artboards lets you manage many icons or related graphics at once.
4. SVG graphics load super fast and are increasingly common in web design.

---

## LinkedIn Learning Tutorials


Watch the entire course if you have time, but I've listed the most essential videos below. It may look like a lot of videos, but I'm tried to cut out the stuff that isn't super relevant to what we'll be doing.



You can skip through some videos if you feel confident, but even I learn new stuff by going through the details like this! Do try and watch all of the selections listed below. The more of them you watch now, the better prepared you will be for this lesson.


**Video Course: [Illustrator CC 2020 Essential Training](https://www.linkedin.com/learning/illustrator-2020-essential-training/color-models-in-illustrator)**


### Essential Videos:


| Chapter | Video |
|----------|--------|
| 2. The Illustrator Environment | _All videos_ |
| 3. Selection | _All videos_ |
| 4. Shape a Line Drawing Tools | Drawing basic shapes |
| 4. Shape a Line Drawing Tools | Drawing polygons and stars |
| 5. Color | The Swatches panel |
| 5. Color | Global swatches |
| 5. Color | Using tints |
| 6. Strokes | Stroke attributes |
| 6. Strokes | Creating arrowheads |
| 8. Alignment, Distribution, and Stacking | Aligning objects |
| 8. Alignment, Distribution, and Stacking | Distributing objects|
| 8. Alignment, Distribution, and Stacking | Using key objects|
| 8. Alignment, Distribution, and Stacking | Changing the stacking order|
| 9.Groups | Working with groups|
| 9. Groups | Using isolation mode |
| 10. Layers | _All videos_
| 11. Transforms | Using the specific Transform tools |
| 12. Drawing by Construction | The Pathfinder panel|
| 12. Drawing by Construction | Clipping masks |
| 13. Drawing Tools| The Pen tool |
| 13. Drawing Tools|The Pencil tool
| 14. Using Guides and Grids | _All videos_ |
| 15. Gradients | Linear gradients |
| 15. Gradients | Freeform gradients |
| 18. Blends, Blending, and Transparency | Using blending modes |
| 19. Appearances | The Eyedropper tool |
| 20. Type | Using point type |
| 20. Type | Using area type |
| 20. Type | Character options |
| 20. Type | Paragraph options |
| 20. Type | Type on a path |
| 20. Type | Outlining type |
| 21. Images in Illustrator |Placing images |
|24. Artboards | _All videos_
| 25. Output | Packaging Illustrator files |
| 25. Output | Export as other file types |
| 25. Output | Asset Export |
| 25. Output | PDF files and Illustrator |



### Some other good videos for advanced use



| Chapter | Video |
|----------|--------|
| 15. Gradients | Freeform gradients
| 17. Symbols | _All videos
| 18. Blends, Blending, and Transparency | Using blends
| Appearances | _All videos_



----

## Using Illustrator for Web Design



In this video, I'll go through the first steps of creating a mockup for a website in Illustrator. This is a more opinionated and advanced video, so if you're new to Illustrator, definitely watch the Essential Training videos above first!



Remember that there are a variety of ways to accomplish some of these things in Illustrator so if you learned something a different way or have a different approach to organizing your design, that's totally fine. With that said, here is an overview of the mockup process and some personal tips and tricks!



[ciscode|rev=1|tool=elmsmedia|item=5937|entity_type=node|render=display_mode|display_mode=full]



## Some Notes on Saving and Exporting


Saving your Illustrator project creates a .ai file that you can open and continue working on at any time.


When you "place" or drag other image files into an Illustrator project, they will either be **embedded** or **linked,** which affects your workflow a bit. I recommend using File » Place to manually control which import method is used. See the video "Placing Images in Illustrator" above for more info. Embedding images increases the files size of your .ai file, and large images can easily balloon your file size to the hundreds of megabytes Which is one reason I usually keep my images "linked." The other advantage of linking is that the images can be dynamically updated \(i.e. edit a photo in Photoshop or replace it with a newer version and it automatically updates in Illustrator \). The complication with "linking" images is that you need to keep track of the original files \(JPEG, PNG, etc.\), so just keep all your project assets together in a single folder and you'll be all set.

One of the most common ways of exporting a final design for this class will be to generate a PDF of all your artboards. I like to do this with **File » Save a copy** and then choose PDF. In the PDF settings window, uncheck the box for "Preserve Illustrator editing capabilities" to rasterize any embedded or linked images and conserve filesize.

If you're exporting ginormous 200MB PDF files that take forever to upload, try that to trim the file size!

The other common export workflow for web design is **File » Export » Export for Screens**. This is similar to the **Asset Export panel** described in a video above, but it also lets you export by Artboard, which is handy if you have mockups of several pages, or a mobile and desktop layout. The Asset Export window lets you generate multiple filetypes and sizes of each item, which is awesome. You can generate PDF files here, if you want each artboard as its own file.
