# Cascading Style Sheets (CSS) 

<img src="https://1000logos.net/wp-content/uploads/2020/09/CSS-Logo.jpg">

## Table of Contents

- [CSS Introduction](#css-introduction)
- [CSS Syntax](#css-syntax)
- [CSS Selectors](#css-selectors)
- [How To Add CSS](#how-to-add-css)
- [CSS Comments](#css-comments)
- [CSS Colors](#css-colors)
- [CSS Backgrounds](#css-backgrounds)
- [CSS Borders](#css-borders)
- [CSS Margins](#css-margins)
- [CSS Padding](#css-padding)
- [CSS Height/Width](#css-heightwidth)
- [CSS Box Model](#css-box-model)
- [CSS Outline](#css-outline)
- [CSS Text](#css-text)
- [CSS Fonts](#css-fonts)
- [CSS Icons](#css-icons)
- [CSS Links](#css-links)
- [CSS Lists](#css-lists)
- [CSS Tables](#css-tables)
- [CSS Display](#css-display)
- [CSS Max-width](#css-max-width)
- [CSS Overflow](#css-overflow)
- [CSS Float](#css-float)
- [CSS Inline-block](#css-inline-block)
- [CSS Combinators](#css-combinators)
- [CSS Opacity](#css-opacity)
- [CSS Navigation Bar](#css-navigation-bar)
- [CSS Dropdowns](#css-dropdowns)
- [CSS Image Gallery](#css-image-gallery)
- [CSS Image Sprites](#css-image-sprites)
- [CSS Attribute Selectors](#css-attribute-selectors)
- [CSS Forms](#css-forms)
- [CSS Website Layout](#css-website-layout)
- [CSS Units](#css-units)
- [CSS Specificity](#css-specificity)
- [CSS !important](#css-important)
- [CSS Math Functions](#css-math-functions)



# CSS Introduction 
## Cascading Style Sheets(CSS) is the language we use to style a Web page.
### What is CSS?
- #### CSS stands for Cascading Style Sheets
 - #### CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- #### CSS saves a lot of work. It can control the layout of multiple web pages all at once
- #### External stylesheets are stored in CSS files
### Why Use CSS?
#### CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.
### CSS Example :
```
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```
- ### CSS Solved a Big Problem.
  #### 1- The style definitions are normally saved in external .css files.
  #### 2- With an external stylesheet file, you can change the look of an entire website by changing just one file!
  # CSS Syntax 
  ### A CSS rule consists of a selector and a declaration block.
  <img src="https://www.w3schools.com/css/img_selector.gif">
  
  ### 1- The selector points to the HTML element you want to style.

  ### 2- The declaration block contains one or more declarations separated by semicolons.
  ### Example  :
  ```
  p {
  color: red;
  text-align: center;
  } 
  ```
  ### Example Explained -
  #### p is a selector in CSS .
  ####  color is a property, and red is the property value.
  #### Text-align is a property, and center is the property value.
  # CSS Selectors 
  ## A CSS selector selects the HTML element(s) you want to style.
  ### We can divide CSS selectors into five categories:
  #### 1- Simple selectors (select elements based on name, id, class)
  #### 2- Combinator selectors (select elements based on a specific relationship between them)
   #### 3- Pseudo-class selectors (select elements based on a certain state)
  #### 4- Pseudo-elements selectors (select and style a part of an element)
  #### 5- Attribute selectors (select elements based on an attribute or attribute value)
   - ##  Example of CSS element Selector.
   ```
   p {
  text-align: center;
  color: red;
  }
  ```
  - ## The CSS id Selector -
   ### The id selector uses the id attribute of an HTML element to select a specific element.
   ## Example :
   ```
   #para1 {
  text-align: center;
  color: red;
  }
  ```
  # How To Add CSS 
  ## When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.
  ## Three Ways to Insert CSS :
  ### There are three ways of inserting a style sheet:
  - #### External CSS
   - #### Internal CSS
  - #### Inline CSS
   ### External CSS ~
   #### With an external style sheet, you can change the look of an entire website by changing just one file!
   ## Example -
   ```
   <!DOCTYPE html>
   <html>
   <head>
   <link rel="stylesheet" href="mystyle.css">
   </head>
   <body>

   <h1>This is a heading</h1>
   <p>This is a paragraph.</p>

   </body>
   </html>
  ```
  ### Internal CSS ~
  #### An internal style sheet may be used if one single HTML page has a unique style.
 ## Example -
 ```
 body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>
```
### Inline CSS ~
#### An inline style may be used to apply a unique style for a single element.
## Example -
```
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
```
# CSS Comments 
## CSS comments are not displayed in the browser, but they can help document your source code.
 <img src="
 https://www.sitesbay.com/css/images/comment.png">
 


# CSS Colors  
## Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.
## CSS color names -
 <img src=
 "https://i.pinimg.com/originals/ad/07/fa/ad07fab27cc455481593fe3704cdd800.png">

 ## CSS Background Color 
 ### You can set the background color for HTML elements:
 <img src=
 "https://static.javatpoint.com/csspages/images/how-to-change-background-color-in-css1.png">

 ## CSS Border Color 
  ### You can set the color of borders:
  <img src=
 "https://cwh-full-next-space.fra1.cdn.digitaloceanspaces.com/tutorial/css-borders/border-color.png">

 # CSS Backgrounds 
 ## The CSS background properties are used to add background effects for elements.
 <img src=
 "https://www.w3docs.com/uploads/media/book_gallery/0001/04/84c973ff9f2a692e53955206135efc18bbb43667.png">

 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_background-color_elements"> You Can Try it Here >>  </a> 

## CSS Background Image -
### The background-image property specifies an image to use as the background of an element.
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_background-image"> You Can Try it Here >>  </a> 
# CSS Borders 
### The CSS border properties allow you to specify the style, width, and color of an element's border.
<img src=
 "https://www.sliderrevolution.com/wp-content/uploads/2021/05/border1.jpg">
 
 ## CSS Border Style -
 ### The border-style property specifies what kind of border to display.
### The following values are allowed:
<img src=
 "https://www.lambdatest.com/blog/wp-content/uploads/2023/02/border-should-always-be-defined-1.jpg">

 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_border-style"> You Can Try it Here :  </a> 
 # CSS Border Width 
 ### The border-width property specifies the width of the four borders.
### The width can be set as a specific size (in px, pt, cm, em, etc) or by using one of the three pre-defined values: thin, medium, or thick:
### <a href="https://w3schools.com/css/tryit.asp?filename=trycss_border-width"> You Can Try it Here >>  </a>
# CSS Margins 
### Margins are used to create space around elements, outside of any defined borders.
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_margin_intro"> You Can Try it Here >> </a>
## Margin Collapse -
### Top and bottom margins of elements are sometimes collapsed into a single margin that is equal to the largest of the two margins.
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_margin_collapse"> You Can Try it Here >>  </a>
# CSS Padding 
### Padding is used to create space around an element's content, inside of any defined borders.
### With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_padding_sides"> You Can Try it Here >> </a>
## Padding - Individual Sides -
### CSS has properties for specifying the padding for each side of an element:

- #### padding-top
- #### padding -right
- #### padding-bottom
- #### padding-left
## Example -
 ```
div {
  padding: 25px 50px 75px 100px;
}
 ```
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_padding_shorthand_3val"> You Can Try it Here >>  </a>
 ## Padding and Element Width -
 ### The CSS width property specifies the width of the element's content area. The content area is the portion inside the padding, border, and margin of an element .
 ## Example -
```
div {
  width: 300px;
  padding: 25px;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_padding_width"> You Can Try it Here >>  </a>
## All CSS Padding Properties :-
<img src=
 "https://www.bitdegree.org/learn/storage/media/images/css-padding.o.png">

## CSS Height, Width and Max-width -
 ### The CSS height and width properties are used to set the height and width of an element.

### The CSS max-width property is used to set the maximum width of an element.
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_height_width_intro"> You Can Try it Here >>  </a>
# CSS Box Model 
 - ### In CSS, the term "box model" is used when talking about design and layout. 
- ### The CSS box model is essentially a box that wraps around every HTML element. It consists of: content, padding, borders and margins. The image below illustrates the box model.
<img src=
 "https://media.geeksforgeeks.org/wp-content/uploads/box-model-1.png">

 ## Explanation of the different parts:
 - ### Content - The content of the box, where text and images appear
- ### Padding - Clears an area around the content. The padding is transparent
 - ### Border - A border that goes around the padding and content
- ### Margin - Clears an area outside the border. The margin is transparent
# CSS Outline 
### An outline is a line drawn outside the element's border.

<img src=
 "https://tutorials.freshersnow.com/wp-content/uploads/2020/02/CSS-Outliners-2.png">

 ## CSS Outline Style -
 ### The outline-style property specifies the style of the outline, and can have one of the following values:

- #### dotted - Defines a dotted outline
 - #### dashed - Defines a dashed outline
 -  #### solid - Defines a solid outline
 - #### double - Defines a double outline
 - #### groove - Defines a 3D grooved outline
 - #### ridge - Defines a 3D ridged outline
 - #### inset - Defines a 3D inset outline
 - #### outset - Defines a 3D outset outline
 - #### none - Defines no outline 
 - #### hidden - Defines a hidden outline
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_outline-style"> You Can Try it Here >>  </a>
## CSS Outline Width,Color,Shorthand,Offset :
### Width :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_outline-width"> You Can Try it Here >>  </a>
### Color :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_outline-color"> You Can Try it Here >>  </a>
### Shorthand :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_outline"> You Can Try it Here >>  </a>
### Offset : 
### <a href="https://www.w3schools.com/css/css_outline_offset.asp"> You Can Try it Here >>  </a>
# CSS Text 
### CSS has a lot of properties for formatting text.
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_text"> You Can Try it Here >>  </a>
## CSS Text Color,Alignment,Decoration,Transformation,Spacing,Shadow :
### Color :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_color"> You Can Try it Here >>  </a>
### Alignment :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_text-align"> You Can Try it Here >>  </a>
### Decoration :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_text-decoration-line"> You Can Try it Here >>  </a>
### Spacing :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_text-indent"> You Can Try it Here >>  </a>
### Transformation :
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_text-transform"> You Can Try it Here >>  </a>
#  CSS Fonts 
### Choosing the right font for your website is important!
## Generic Font Families -
### In CSS there are five generic font families:
#### 1- Serif - fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
#### 2- Sans-serif - fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
 #### 3- Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 
 #### 4- Cursive - fonts imitate human handwriting.
 #### 5- Fantasy - fonts are decorative/playful fonts.
 <img src=
 "https://www.hubspot.com/hs-fs/hubfs/web-safe-html-css-fonts_14.webp?width=650&height=450&name=web-safe-html-css-fonts_14.webp">
 
 ## The CSS font-family Property :
 ##### Note: If the font name is more than one word, it must be in quotation marks, like: "Times New Roman".
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_font-family"> You Can Try it Here >>  </a>
 ## CSS Web Safe Fonts :
  ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_font-family2"> You Can Try it Here >>  </a>
  ## CSS Font Fallbacks :
  <img src=
 "https://www.html-seminar.de/bilder/schriftarten-sortiert.png">
  
  # CSS Icons 
  ### Icons can easily be added to your HTML page, by using an icon library.
   <img src=
 "https://www.devwares.com/static/4a29c6f2037077124e7df812f0d32a71/63ec5/cssImage2.png">

  ## How to add Icons :
  ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_icons_fa"> You Can Try it Here >>  </a>
  # CSS Links 
  ### With CSS, links can be styled in many different ways.
   <img src=
 "https://www.munnelly.com/webdesign/exercises/assets/img/hyperlinks-styles/link-states-active.png">
  ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_link"> You Can Try it Here >>  </a>
  # CSS Lists
  ### Lists are used to display a collection of items.Lists are a fundamental part of HTML and can be styled in various ways using CSS to enhance their appearance and functionality. 
 ## Types of Lists in HTML :
 ### 1- Unordered Lists .
 ### 2- Ordered lists .
 ## Example of both lists :
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-type_ex"> You Can Try it Here >>  </a>
 
 # CSS Tables 
 ### The look of an HTML table can be greatly improved with CSS:
 <img src=
 "https://wpdean.com/wp-content/uploads/2023/11/image-2023-11-01T124836.640.jpg">
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_table_fancy"> You Can Try it Here >>  </a>

 ## Table Border -
 ### To specify table borders in CSS, use the border property.
 <img src=
 "https://i.sstatic.net/tg2Jl.png">
 
 ## Table Size :
 ### Table Width and Height -
 #### The width and height of a table are defined by the width and height properties.
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_table_width2"> You Can Try it Here >>  </a>
## CSS Table Alignment -
 ### 1- Horizontal Alignment : 
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_table_vertical-align"> You Can Try it Here >>  </a>
### 2- Vertical Alignment :
 ### <a href="https://w3schools.com/css/tryit.asp?filename=trycss_table_align"> You Can Try it Here >>  </a>
## CSS Responsive Table :
### A responsive table will display a horizontal scroll bar if the screen is too small to display the full content.
 <img src=
 "https://shots.codepen.io/username/pen/yaLRjd-800.jpg?version=1485045257">
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_table_responsive"> You Can Try it Here >>  </a>

 ## CSS Layout - The display Property :
 - ### The display property is used to specify how an element is shown on a web page.
- ### Every HTML element has a default display value, depending on what type of element it is. The default display value for most elements is block or inline.
## Block-level Elements -
#### A block-level element ALWAYS starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
## Inline Elements -
####  An inline element DOES NOT start on a new line and only takes up as much width as necessary.
### Example Of Both :
<img src=
 "https://ictacademy.com.ng/wp-content/uploads/2017/10/inline-block-and-positioning-in-css-4-638.jpg">
 
 # CSS Layout - width and max-width :
 ### Setting the width of a block-level element will prevent it from stretching out to the edges of its container. Then, you can set the margins to auto, to horizontally center the element within its container. The element will take up the specified width, and the remaining space will be split equally between the two margins:
 ## Example -
 ```
 div.ex1 {
  width: 500px;
  margin: auto;
  border: 3px solid #73AD21;
}

div.ex2 {
  max-width: 500px;
  margin: auto;
  border: 3px solid #73AD21;
}
 ```
 # CSS Overflow 
 ### The CSS overflow property controls what happens to content that is too big to fit into an area.
  ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_overflow_intro"> Try it Yourself  >>  </a>
  # >CSS Layout - float and clear :
### The CSS float property specifies how an element should float.
### The CSS clear property specifies what elements can float beside the cleared element and on which side.
<img src=
 "https://blog.openreplay.com/images/working-with-css-float-and-clear-properties/images/hero.png">
 
 ## Example :
 ```
 img {
  float: right;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_layout_float"> Try it Yourself  >>  </a>
## CSS Layout - clear and clearfix :
### The clear property specifies what should happen with the element that is next to a floating element.
## Example :
```
div1 {
  float: left;
}

div2 {
  clear: left;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_layout_clear"> Try it Yourself  >>  </a>
# CSS Inline-Block 
### Compared to display: inline, the major difference is that display: inline-block allows to set a width and height on the element.
## Example :
```
span.a {
  display: inline; /* the default for span */
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue;
  background-color: yellow;
}
```
## Using inline-block to Create Navigation Links -
#### One common use for display: inline-block is to display list items horizontally instead of vertically.
## Example :
```
 .nav {
  background-color: yellow;
  list-style-type: none;
  text-align: center; 
  padding: 0;
  margin: 0;
}

.nav li {
  display: inline-block;
  font-size: 20px;
  padding: 20px;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_inline-block_nav"> Try it Yourself  >>  </a>
# CSS Combinators 
### A combinator is something that explains the relationship between the selectors.
## There are four different combinators in CSS:
 - ### `Descendant selector (space)` - The descendant selector matches all elements that are descendants of a specified element.
 - ### `Child selector (>)` - The child selector selects all elements that are the children of a specified element.
 - ### `Adjacent sibling selector (+)` - The adjacent sibling selector is used to select an element that is directly after another specific element. 
 - ### `General sibling selector (~)` - The general sibling selector selects all elements that are next siblings of a specified element.
  # CSS Opacity 
  ### The opacity property specifies the opacity/transparency of an element.
 ## Transparent Image -
 ### The opacity property can take a value from 0.0 - 1.0. The lower the value, the more transparent.
 <img src=
 "https://global.discourse-cdn.com/freecodecamp/original/3X/b/b/bb37499c3c62d59d3943bfb208b3eaa8501ec11e.jpg">
 
 ## Example :
 ```
  img {
  opacity: 0.5;
}

img:hover {
  opacity: 1.0;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_image_transparency2"> `Try it Yourself  >>`  </a>
# CSS Navigation Bar 
 - ### Having easy-to-use navigation is important for any web site.
 - ### With CSS you can transform boring HTML menus into good-looking navigation bars.
 ## Example :
 ```
 <ul>
  <li><a href="default.asp">Home</a></li>
  <li><a href="news.asp">News</a></li>
  <li><a href="contact.asp">Contact</a></li>
  <li><a href="about.asp">About</a></li>
</ul>
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_navbar_basic_html"> `Try it Yourself  >>`  </a>
## Vertical Navigation Bar :
### To build a vertical navigation bar, you can style the `<a>` elements inside the list, in addition to the code from the previous page.
<img src=
 "https://www.campuslife.co.in/Html/image/vertical-menu-image.jpg">

 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_navbar_vertical_borders"> `Try it Yourself  >>`  </a>
 ## Horizontal Navigation Bar :
 ### There are two ways to create a horizontal navigation bar. Using inline or floating list items.
 <img src=
 "https://www.websiterealizer.com/help/drex_how-to-create-a-horizontal-navigation-bar-from-scratch_custom.png">

  ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_navbar_horizontal_black"> `Try it Yourself  >>`  </a>
  # CSS Dropdowns  
   ### Create a dropdown box that appears when the user moves the mouse over an element.
   <img src="https://i.sstatic.net/g7iRI.jpg">
   
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_dropdown_button"> `Try it Yourself  >>`  </a>
## Dropdown Navbar -
 ### How to add a `dropdown` menu inside a navigation bar-
 ### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_dropdown_navbar2"> `Try it Yourself  >>`  </a>
# CSS Image Gallery 
### CSS can be used to create an image gallery.
<img src="https://www.codingnepalweb.com/wp-content/uploads/2023/05/Filterable-Image-Gallery-in-HTML-CSS-Bootstrap-JavaScript.jpg">

## Example :
```
<div class="gallery">
  <a target="_blank" href="img_5terre.jpg">
    <img src="img_5terre.jpg" alt="Cinque Terre" width="600" height="400">
  </a>
  <div class="desc">Add a description of the image here</div>
</div>
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_image_gallery_responsive"> `Try it Yourself  >>`  </a>
# CSS Image Sprites 
 - ### An image sprite is a collection of images put into a single image.
 - ### Using image sprites will reduce the number of server requests and save bandwidth.
 <img src="https://i.sstatic.net/fu607.png">

## Example :
```
#home {
  width: 46px;
  height: 44px;
  background: url(img_navsprites.gif) 0 0;
}
```
## Example Explained -
 - #### `<img id="home" src="img_trans.gif">` - Only defines a small transparent image because the src attribute cannot be empty. The displayed image will be the background image we specify in CSS
 - #### `width: 46px; height: 44px;` - Defines the portion of the image we want to use
 - #### `background: url(img_navsprites.gif) 0 0;` - Defines the background image and its position (left 0px, top 0px)
# CSS Attribute Selectors 
### The `[attribute] selector` is used to select elements with a specified attribute.

 <img src="https://miro.medium.com/v2/resize:fit:1400/0*d88xdnAWSuocM3ut.png">
 
 ## Example :
 ```
 a[target] {
  background-color: yellow;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_sel_attribute_hyphen"> `Try it Yourself  >>`  </a>
# CSS Forms 
### The look of an HTML form can be greatly improved with CSS.
<img src="https://i.ytimg.com/vi/okbByPWS1Xc/hq720.jpg?sqp=-oaymwEXCK4FEIIDSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLBCkj5Mg7P7u5iZR-VM-Zh_j_yGYA">

## Example :
```
input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_forms"> `Try it Yourself  >>`  </a>

# CSS Website Layout 
### A website is often divided into headers, menus, content and a footer.
<img src="https://miro.medium.com/v2/resize:fit:1400/1*ia4V5qfk6Ki3iWIn-SmErw.png">

## Header -
 ### A header is usually located at the top of the website (or right below a top navigation menu). It often contains a logo or the website name.
 ## Example :
 ```
 .header {
  background-color: #F1F1F1;
  text-align: center;
  padding: 20px;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_website_layout_header"> `Try it Yourself  >>`  </a>
## Navigation Bar -
#### A navigation bar contains a list of links to help visitors navigating through your website.
## Example :
```
}

/* Navbar links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_website_layout_navbar"> `Try it Yourself  >>`  </a>
# CSS Units 
 ### CSS has several different units for expressing a length.
 - ### Many CSS properties take "length" values, such as width, margin, padding, font-size, etc.

 - ### Length is a number followed by a length unit, such as 10px, 2em, etc.
 <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--a4-V95uf--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2v0z3jkdsqzhgi7kfcj5.png">
 
 ## Example :
 ### Set different length values, using px (pixels).
 ```
 h1 {
  font-size: 60px;
}

p {
  font-size: 25px;
  line-height: 50px;
}
```
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_units_px"> `Try it Yourself  >>`  </a>
## CSS The !important Rule  
 ### The `!important` rule in CSS is used to add more importance to a property/value than normal.
### In fact, if you use the `!important rule`, it will override ALL previous styling rules for that specific property on that element!.
## Example :
```
#myid {
  background-color: blue;
}

.myclass {
  background-color: gray;
}

p {
  background-color: red !important;
}
```
## Example Explained :
### In the example above. all three paragraphs will get a red background color, even though the ID selector and the class selector have a higher specificity. The `!important rule` overrides the `background-color` property in both cases.
### <a href="https://www.w3schools.com/css/tryit.asp?filename=trycss_important"> `Try it Yourself  >>`  </a>
# CSS Math Functions 
### The CSS math functions allow mathematical expressions to be used as property values. Here, we will explain the `calc()`, `max()` and `min()` functions.
## The calc() Function -
### The `calc() function` performs a calculation to be used as the property value.
<img src="https://www.i2tutorials.com/wp-content/media/2020/12/calc.jpg">

## The max() Function -
### The `max() function` uses the largest value, from a comma-separated list of values, as the property value.
<img src="https://assets.htmlgoodies.com/uploads/2022/03/CSS-max-function.jpg">

## The min() Function -
### The `min() function` uses the smallest value, from a comma-separated list of values, as the property value.
<img src="https://i.ytimg.com/vi/CbIt7nWW58s/oar2.jpg?sqp=-oaymwEYCJUDENAFSFqQAgHyq4qpAwcIARUAAIhC&rs=AOn4CLA0oVUMJ9f9pkFtCKIg6APveHD7cw">

## Reference Link :
## <a href="https://www.w3schools.com/css/default.asp"> `Link  >>`  </a>
## <a href="https://www.javatpoint.com/css-font-weight"> `Link  >>`  </a>
## <a href="https://www.w3schools.com/css/css_math_functions.asp"> `Link  >>`  </a>
## <a href="https://en.wikipedia.org/wiki/CSS"> `Link  >>`  </a>










































  
  


























 







 









  

