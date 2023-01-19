# HTML & CSS Full Course - Beginner to Pro (2022)

This is code for the [HTML & CSS Full Course - Beginner to Pro (2022)](https://www.youtube.com/watch?v=G3e-cpL7ofc) by SuperSimpleDev.

View the html files in this project by opening them in Google Chrome.

&nbsp;



## 1. HTML Basics

To begin, create a website.html file that will contain the website code.

Elements are parts of a web page.

HTML tags are enclosed in ```<> </>``` brackets, and are used to create elements.

```<button>``` is the button element, ```<p>``` is the paragraph element, and ```<a>``` is the anchor element, which is used to link to other web pages.

HTML attributes provide additional information about an element.

In a link, the ```href="https://www.youtube.com"``` attribute specifies the URL to link to.

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

The ```<span>``` text element is a generic text element that can be styled using CSS.

Use the margin-left property to display multiple spaces between text.

&nbsp;



## 6. The HTML Structure

An HTML page is structured with ```<html>```, ```<head>``` and ```<body>``` elements.

The ```<head>``` element should contain all elements that are not visible on the page, such as the ```<style>``` tag and page title.

The ```<body>``` element should contain all visible elements on the page.

### Moving CSS to a .css File

To improve organization, we can move all of the CSS to a .css file.

To link the CSS file to the HTML file, use the ```<link>``` tag.

Use the ```rel``` and ```href``` attributes inside the link tag to link the file:

```<link rel="stylesheet" href="filename.css">```

The CSS file must be in the same folder as the HTML file, otherwise the directory of the CSS file must be specified:

```<link rel="stylesheet" href="styles/filename.css">```

#### Adding New Fonts from Google

We will add the Roboto font to our text.html file.

Go to fonts.google.com, search for Roboto, and select the Regular 400 and Bold 700 styles.

Copy the HTML code for the fonts and add it to the ```<head>``` section of the .html file.

In the corresponding .css file, we can now use the Roboto font.

&nbsp;



## 7. Images and Text Boxes

The rest of this course will be dedicated to recreating YouTube's home page in HTML and CSS.

This will be done in the youtube.html file.

### Adding Images

The ```<img>``` tag is used to add an image to a web page.

Use the ```src``` attribute to link the image file:

```<img src="imagename.jpg">```

If the image is not in the same folder as the HTML file, we must specify a path:

```<img src="images/imagename.jpg">```

Images can be styled in CSS with properties such as width, height, object-fit, object-position, border-width, etc.

## Adding a Text Box (Search Bar)

We can use a text box as the input for a search bar.

To display a text box, use the ```<input>``` element with the ```type="text"``` attribute:

```<input type="text">```

Use the ```placeholder``` attribute to add placeholdler text to the text box.

