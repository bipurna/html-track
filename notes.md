# HTML, CSS, and JavaScript

## Websites Summarry

+ There are two types of websites - static and dynamic.

+ Static websites have fixed content that does not change.

+ Content in a dynamic website can change, either by users or automatically for different users

+ HTML, CSS, and JavaScript are the three core technologies of the World Wide Web(WWW).

+ HTML elements are accessed using angular brackets, or commonly known as tags. These tags are used to create the structure for a web page.

+ CSS is used to enhance the appearance of a web page.

+ JavaScript is a scripting language that plays a vital role in developing dynamic websites. It is used for user interaction, content management, manipulating databases, and many more.

## Uderstanding HTML elements, tags, and attributes

### minimalist webpage tag

```html
<!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body>
    </body>
</html>
```

### HTML attributes

+ Most of the HTML tags have additional properties or characteristics that are defined by attributes. For Example;

 ```html 
 <img src="" alt="" />
 ```

### Closing and opening tags

+ The difference between the opening and closing tag is  that the closing tag has a forward slash.

### <! DOCTYPE html>

 This is the declaration that informs the browser that it is an HTML document.

## Uderstanding HTML elements, tags, and attributes summary

+ The ```<html>``` tag is used to define an HTML document that contains all other tags.

+ The content of an HTML document is defined inside the ```<body>``` tag.
+ The ```<head>``` tag has all the information regarding the document.
+ The attributes define the additional properties or characteristics for an HTML tag.
+ The closing tag has a forward slash in it.
+ Declare the ```<!DOCTYPE html>``` at the top and always save the file with .html extension.

## Paragraphs and headings

+ The most common content you can find on any web page is the simple text.

+ create paragraphs of any length, headings of any size, and you can change color, font size, font style, background-color.

### `<p>` tag

+ A paragraph in HTML is added using the ```<p>``` tag. For headings, we have multiple tags. These include `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, and `<h6>`, each of them having a different size.

  + ```<p> Hello World </p>```

### Line break

+ Each paragraph starts with new line but to insert new line withing the paragraph HTML provides the `<br>` tag. For example;

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
</head>
<body>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Saepe dolores alias quasi qui natus. Fuga, ratione ab sint debitis beatae, repellendus optio dolores odit dolorum perferendis tempore, fugit reprehenderit quos!</p>
    <p>Lorem ipsum, dolor sit amet <br>consectetur adipisicing elit. Saepe<br> dolores alias quasi qui natus. Fuga,<br> ratione ab sint debitis beatae,<br> repellendus optio dolores odit dolorum<br> perferendis tempore, fugit<br> reprehenderit quos!</p>
</body>
</html>
``` 

### headings

+ HTML provides  `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, and `<h6>` heading tags.
For example;

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
</head>
<body>
    <h1>Lorem ipsum, dolor sit amet </h1>
    <h2>consectetur adipisicing elit. </h2>
    <h3>Saepe dolores alias quasi qui natus.</h3> 
    <h4>Fuga, ratione ab sint debitis beatae,</h4> <h5>repellendus optio dolores odit dolorum </h5>
    <h6>perferendis tempore, fugit reprehenderit quos!</h6>
</body>
</html>

```

+ The `<h1>` has the largest size while the `<h6>` has the smallest.

## Text Formatting

+ enclosed with `<b></b>` will be bold and with `<strong></strong>` as well bold with extra meaning.

+ enclosed with `<i></i>` will be italisized and with `<em></em>` will emphasized.

+ `<small></small>` made, text enclosed by, smaller than other in appearance.

+ `<del></del>` makes strikethrough line.

+ `<mark></mark>` highlights the texts with yellow color that enclosed by this tags.

+ `<sub></sub>` defines subscripted text and `<sup></sup>` defines superscripted text.

## hyperlinks

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
</head>
<body>
    <h1>Lorem ipsum,<a href="https://google.com" target="_blank" title="Go to google">dolor</a> sit amet </h1>
    
</body>
</html>

```

### target attributes

+ _self : open link in a same tab

+ _blank : open link in new tab

+ _top : open link in the full body of the window

+ _parent : open link in the parent frame

### title attirbute

+ title of the hyperlink

## summary

+ The `<a>` tag in HTML is used to create hyperlinks.
+ The href attribute is mandatory because it holds the URL of the document or web page that will open.
+ The target attribute specifies where the document or web page will open.
+ Use '_blank' as the value of the target attribute to open the document in a new tab/window.
+ The title holds the extra information that will appear when hovered over the hyperlink.
+ Images and buttons can also work as hyperlinks.

## Images

+ `<img>` tag does not have a corresponding closing.

+ The src attribute is mandatory while it holds the URL of the image including name and extension.

```html
<body>
    <img src = "me.jpg" width="" height="" alt="">
</body>
```

+ it has alt attribute that displays while faild to load image.

+ image with link: must wrap with a tag.
