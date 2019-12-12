If you watched the Webflow 101 Crash Course videos \(especially the ones in the "Layout" section\), you should have some idea of how to develop basic layouts with the tools available in Webflow. But as you begin to translate your mockups into functional websites, there are always a lot of questions about how to position elements where you want them. So, let's review some of the tools for layout in CSS.

Recall that be default, HTML places elements below each other, from top to bottom, and aligned to the left of the page. That default behavior can often be good enough to show several paragraphs or images in a column, so before you go crazy with layout properties, just place in your HTML content in the order you would read it and see how it looks. 

How do I center things?

Webflow has a container element that acts as a central content area. This is great for articles layouts where you want to keep text from spanning the entire page width. Note that content will still align to the left edge of the container, but that's great for reading paragraphs of text! 

Here's a guide to all the centering methods you might need, but these are the most common ones I think you'll use:

Properties for the parent element:

* text-align: center — aligns text to the center. Just like a word processor. 
* display: flex — arranges children in a one-direction axis \(a row or column\); easily centers things horizontally and vertically. Allows you to control space between elements too.
* display: grid — arranges children in a two-directional grid \(X and Y coordinates set by column and row numbers\). 

Properties for child elements

* margin: 0 auto — That's "0" \(zero\) for the top and bottom values, and "auto" for left and right. This centers content horizontally; if it's not working, set the child element to "display: block". 

What about those top, left, right, and bottom values? 

These properties may look tempting in the Webflow styles panel, but you should only use these if the element you're working with has it's positon property set to relative, absolute, or fixed. These are all relatiely uncommon techniques for placing content and should only be used in specific cases. There's a video about these in the [Crash Course](https://university.webflow.com/courses/webflow-101-crash-course) or you can [read about them here](https://university.webflow.com/article/position-floats-and-clear-settings). 

TLDR: 

* Relative positioning nudges elements from where they would appear otherwise. This is useful if you want elements to overlap in weird ways. 
* Abosulte positioning places elements within a parent set to relative position. This gets confusing and you probably don't need to worry about it. 
* Fixed positioning locks elements in palce relative to the browser viewport \(e.g. a nav bar that stays stuck at the top of the sceen as you scroll—if you want to do that, set "top: 0" and "left: 0"\). 

What about margins and padding?

These are great tools for tweaking the placement of elements. These are usually best deployed for small values where you need some extra space between things. If you use large margin values to push content around the page, you will probably run into trouble when the browser resizes. Note that you can use % instead of px as your unit \(e.g. margin: 10%\) to make margins and paddings flexible instead of one fixed value.





