This exercise is designed to let you play around with HTML and CSS elements to learn how they work in a fun, interactive experiment.

The sample webpage includes a button. When you click the button, a new "class" is applied to the  &lt;body&gt; element. By targeting elements with CSS you can create new visual styles for the websites "initial" \(when the page first loads\) and "active" \(after the button is clicked\) states.

In other words, you can click the button and make things flash and change colors.

### Requirements

* Add at least one additional HTML element.
* Add CSS properties to change the appearance of the site in the "initial" and "active" states.
* Create a sense of surprise when the button is clicked.

### Instructions

1. Download and install an Integrated Development Environment \(IDE\) like Brackets or Atom.
2. Download the sample HTML file. This file can be opened in a web browser to view the rendered web page. Open the file in your IDE to edit the code. If using Brackets, click the lightening icon to view a "live preview" of the site that will auto-update as you make changes to the code.
3. Examine the code and try changing values or adding/deleting things to see what happens. If you mess things up, you can always hit Undo or download the file again.
4. Add at least one new HTML text element to the page, such as as paragraph, header, ordered or unordered list. You can use emojis or glyphs. ✌️
5. Change the CSS properties for some of the HTML elements to customize the initial state of the website. Some good properties to try include:
6. * background-color
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
7. Now create additional CSS properties for the "active" state of the page. The goal is to have the site's appearance change when the button is clicked. Make it a big, dramatic shift so that clicking the button really surprises the user. You must \_at least \_change the "Let's dance" header and the background colors, but try playing with some of the properties above.
8. You don't need to understand the javascript at the bottom of the page, but what it does is add or remove the class "active" to the \`&lt;body&gt;\` element every time the button is clicked. So to set the color of the \`h1\` in the initial state, you would write \`h1 {color: purple;}\`and to target it while the body has the "active" class, you would write body.active \`h1 {color: orange;}\` — Note the space between the selector elements. Read more about [CSS selectors](https://www.w3schools.com/csSref/css_selectors.asp) for reference.
9. Recap: any HTML element can one set of CSS properties in the "initial" state, and a second set of properties in the site's "active" state. Have fun!

NOTE: This file includes the CSS within the &lt;head&gt; of the HTML file between the &lt;style&gt; tags. More often, developers put the CSS in a separate .css file and "connect" it to the HTML file. This more clearly separates the content from the style and avoids scrolling through enormous lengths of code. But to keep things simple for now, everything is in one file.

