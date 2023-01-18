# HTML & CSS Full Course - Beginner to Pro (2022)

This is code for the [HTML & CSS Full Course - Beginner to Pro (2022)](https://www.youtube.com/watch?v=G3e-cpL7ofc) by SuperSimpleDev.

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




