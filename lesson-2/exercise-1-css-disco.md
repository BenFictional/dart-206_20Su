This exercise is designed to let you play with HTML and CSS elements and learn how they work in a fun, interactive experiment.


The sample webpage includes a button. When you click the button, a new "class" is applied to the `<body>` element. By targeting elements with CSS you can create new visual styles for the website's "initial" \(when the page first loads\) and "active" \(after the button is clicked\) states.


In other words, you can click the button and make things flash and change colors. Or appear and disappear. Or whatever you can think of. 


We'll start with a simple [template on Glitch]([CSS Disco template](https://glitch.com/~css-disco-button)) that switches colors when the button is clicked, but here's a more complex example of what you might create:


[ADD DISCO DEMO GIF HERE]


What properties are changing when the button is clicked? You can examine the code for the [Watermelon Demo](https://glitch.com/~watermelon-disco-demo) in a separate Glitch project to see how it's made. 



### Requirements

* Add at least one additional HTML element.
* Add CSS properties to change the appearance of the site in the "initial" and "active" states.
* Create a sense of surprise or drama when the button is clicked.


### Instructions


1. Visit the [CSS Disco template](https://glitch.com/~css-disco-template) on Glitch. 
2. Click the "Remix" button to create your own variant of the site. 
3. Examine the code and try changing values or adding/deleting things to see what happens. If you mess things up, you can always hit Undo or download the file again.
4. Add at least one new HTML text element to the page, such as as paragraph, header, ordered or unordered list. You can use emojis or glyphs. ✌️ You can add images by placing them in your site's Assets folder and linking to them as [<img>](https://www.w3schools.com/tags/tag_img.asp) objects in HTML or [background-images](https://www.w3schools.com/css/css_background.asp) in CSS. 
5. Change the CSS properties for some of the HTML elements to customize the "initial" state of the website. Some good properties to try include:
    * background-color
    * background: linear-gradient\(\) — [Generate gradients here](https://cssgradient.io/)
    * color
    * font-size
    * font-family
    * border
    * border-radius
    * margin
    * padding
    * transform:rotate
    * opacity
7. Now create additional CSS properties for the "active" state of the page. The goal is to have the site's appearance change when the button is clicked. Make it a __big, dramatic shift__ so that clicking the button really surprises the user. You must _at least_change the sample header and the background colors, but try playing with some of the properties above.
8. You don't need to understand the javascript in the scripts.js file, but what it does is add or remove the class "active" to the `<body>` element every time the button is clicked. So to set the color of the `h1` in the initial state, you would write `h1 {color: purple;}`and to target it while the body has the "active" class, you would write `body.active h1 {color: orange;}` — Note the space between the selector elements. Read more about [CSS selectors](https://www.w3schools.com/csSref/css_selectors.asp) for reference.
9. Recap: any HTML element can have one set of CSS properties in the "initial" state, and a second set of properties in the site's "active" state. Have fun!

## Submission


Your Glitch projects are automatically public on the web and can be shared with the project URL, like "https://glitch.com/~css-disco-template"

Submit your project's URL to Canvas. 

