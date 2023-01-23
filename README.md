# HTML & CSS Full Course - Beginner to Pro (2022)

This is code for the [HTML & CSS Full Course - Beginner to Pro (2022)](https://www.youtube.com/watch?v=G3e-cpL7ofc) by SuperSimpleDev.

View the html files in this project by opening them in Google Chrome.

&nbsp;



## 1. HTML Basics

To begin, create a website.html file that will contain the website code.

Elements are parts of a web page.

HTML tags are enclosed in `<> </>` brackets, and are used to create elements.

`<button>` is the button element, `<p>` is the paragraph element, and `<a>` is the anchor element, which is used to link to other web pages.

HTML attributes provide additional information about an element.

In a link, the `href="https://www.youtube.com"` attribute specifies the URL to link to.

The target attribute specifies whether to open the link in the current page or a new tab.

Attributes are seperated by spaces in the tag.

Extra spaces and newline characters are ignored in HTML files.

&nbsp;



## 2. CSS Basics

In this part, we will create three buttons and use CSS to style them.

CSS stands for Cascading Style Sheets, and is used to specify how HTML elements appear on screen.

CSS can be added to an HTML file using the ```<style>``` tag.

A CSS Selector refers to the name of the element we are styling (ex: button)

A CSS Property refers to the property of the element we are changing (ex: background-color)

The CSS Value is on the right of the property, and is the value we are changing the property to (ex: red)

CSS styles are seperated with a semi-colon.

Color values can be displayed using RGB (ex: rgb(200, 0, 0))

### CSS Classes

The class attribute for an HTML element lets us label the element (ex: class="subscribe-button")

To style a class in CSS, use a period (ex: .subscribe-button)

Using a period means that we are targeting a class instead of an element.

Multiple elements can have the same class name.

### Margin

In CSS, space around an element is called the margin.

Use the margin properties to add a top, bottom, left or right margin to an element (ex: margin-right: 8px)

A general technique for CSS is to create an HTML element and style each property one-by-one until the desired appearance is achieved. 

&nbsp;



## 3. Hovers, Transitions, Shadows

In this part, we will use CSS to create hovers, transitions and shadows for our buttons.

### Hovers

Buttons can change their styles when the cursor hovers over them.

To create CSS for a button while hovering, use the :hover keyword in the class name (example: background-color:hover)

The background-color:hover class is called a pseudo-class.

The :active pseudo-class is applied when the button is being clicked on.

### Transitions

Transition properties are added to the class properties, not the pseudo-class.

The transition property take two values, what we want to transition (opacity) and a value in seconds.

To transition multiple properties at once, seperate them with a comma.

### Shadows

Use the box-shadow property to add a shadow to a button.

The first value represents the horizontal position of the shadow.

The second value represents the vertical position of the shadow.

The third value represents the shadow blur.

The last value represents the shadow color.

Use an rgba() value which will set the color, as well as the opacity.

&nbsp;



## 4. Chrome DevTools & CSS Box Model

### Chrome Devtools

The Chrome DevTools can be opened in Google Chrome by right clicking on a web page and choosing Inspect.

It displays the website's HTML and CSS properties for any element you select.

Click on the pointer icon in the top left to show the HTML for any element you hover over.

The DevTools can be used to find the exact hex color values of an element, as well as height, width and all other attributes.

### CSS Box Model

Margin is the spacing on the outside of an element. 

Padding is the spacing on the inside of an element.

It's better to set margins and padding instead of height and width, because you don't need to recalculate dimensions if the text changes.

In the Computed tab of DevTools, you can see the padding, margin and border dimensions of an element. 

The CSS box model is how much space an element takes up and how far away it is from other elements.

The vertical-align property will align the buttons to the top.

&nbsp;



## 5. Text Styles

In this part, we use CSS to style text.

In text.html, add HTML and CSS to style the title, stats, author and description of a YouTube style video. 

The font-size property is used to change the text size.

The font-family property is used to change the text font.

HTML entities are used to display special characters.

When a property is set multiple times, the selector (property) that is more specific has higher priority.

This is known as CSS Specificity.

A text element is an element within a line of text that modifies the text.

The `<span>` text element is a generic text element that can be styled using CSS.

Use the margin-left property to display multiple spaces between text.

&nbsp;



## 6. The HTML Structure

An HTML page is structured with `<html>`, `<head>` and `<body>` elements.

The `<head>` element should contain all elements that are not visible on the page, such as the `<style>` tag and page title.

The `<body>` element should contain all visible elements on the page.

### Moving CSS to a .css File

To improve organization, we can move all of the CSS to a .css file.

To link the CSS file to the HTML file, use the `<link>` tag.

Use the `rel` and `href` attributes inside the link tag to link the file:

`<link rel="stylesheet" href="filename.css">`

The CSS file must be in the same folder as the HTML file, otherwise the directory of the CSS file must be specified:

`<link rel="stylesheet" href="styles/filename.css">`

#### Adding New Fonts from Google

We will add the Roboto font to our text.html file.

Go to fonts.google.com, search for Roboto, and select the Regular 400 and Bold 700 styles.

Copy the HTML code for the fonts and add it to the `<head>` section of the .html file.

In the corresponding .css file, we can now use the Roboto font.

&nbsp;



## 7. Images and Text Boxes

The rest of this course will be dedicated to recreating YouTube's home page in HTML and CSS.

This will be done in the youtube.html file.

### Adding Images

The `<img>` tag is used to add an image to a web page.

Use the `src` attribute to link the image file:

`<img src="imagename.jpg">`

If the image is not in the same folder as the HTML file, we must specify a path:

`<img src="images/imagename.jpg">`

Images can be styled in CSS with properties such as width, height, object-fit, object-position, border-width, etc.

### Adding a Text Box (Search Bar)

We can use a text box as the input for a search bar.

To display a text box, use the `<input>` element with the `type="text"` attribute:

`<input type="text">`

Use the `placeholder` attribute to add placeholdler text to the text box.

&nbsp;



## 8. CSS Display Property

In HTML, there are three types of elements:

1. Block element: An element that takes up an entire line

2. Inline-block element: An element that only takes up as much space as it needs to, and does not take up an entire line

3. Inline element: An element that appears within a line of text

The display property can be used to switch between block and inline-block displays. 

To set the display property, use the following CSS: `display: inline-block;` or `display: block;`

&nbsp;



## 9. The div Element

The `<div>` element is the most important HTML element.

It is used as a container for other HTML elements.

Div stands for division, and the div element is a box that is used for holding other elements.

A div can contain any other elements inside it, including other divs.

It is helpful to set the display property of a div to inline-block so it doesn't take up an entire line.

We can use the `vertical-align: top;` property to align divs at the top.

&nbsp;



## 10. Nested Layouts Technique

This is the most important lesson of the course.

There are two main types of layouts: 

1. Vertical Layout: Elements are stacked on top of each other

2. Horizontal Layout: Elements are placed beside each other

By using a combination of vertical and horizontal layouts, we can create almost any layout we see on a website.

By default, a div is a block element (it takes up the entire line).

Use the `display: inline-block` property to add elements horizontally. 

Use the width property to assign widths to elements in a div.

&nbsp;



## 11. CSS Grid

CSS Grid is used to create perfectly aligned horizontal layouts.

We will use the CSS Grid layout to display all of the YouTube video previews.

A grid is a layout with rows and columns.

It is more accurate than using the inline-block method, and does not leave unwanted gaps between elements.

To create a grid using CSS, set the display property of a div to `display: grid`.

To set the amount of columns and the width of each column, use the `grid-template-columns` property.

When there are more elements than columns, the elements will wrap around to the first column.

Use the `1fr` value to take up the remaining amount of free space on a page.

The number in front of `fr` is the ratio of remaining free space that will be taken up.

To create spaces in the grid, use the `column-gap` and `row-gap` property.

&nbsp;



## 12. Flexbox

Flexbox is another way to create layouts in CSS.

We will use flexbox to create the YouTube header at the top of the page.

To create a flexbox using CSS, set the `display:` property of the div to `flex`.

To make an element take up the rest of the page, use the `flex: 1` property.

The number after `flex` is the ratio of remaining free space that will be taken up.

The difference between grid and flexbox is that the grid layout is rigid and flexbox is flexible in terms of dimensions.

It is also more useful when the number of elements in a div will change.

Use the `justify-content` property to align the elements horizontally, like `start`, `end` or `center`.

The `justify-content: space-between` property will space out the elements horizontally.


Use the `align-items` property to align elements vertically, like `start`, `end` or `center`.

&nbsp;



## 13. Nested Flexbox

In this part, nested flexboxes are used to create the top header bar.

The header is split into left, middle and right sections.

Icons are added to the header and CSS classes are used to style them.

The `flex-shrink: 0` property is used to prevent a flex box from shrinking past its minimum width.

&nbsp;



