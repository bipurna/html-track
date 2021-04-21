# HTML - HyperText MarkUp Language

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

## Tables

+ Tables are considered one of the best ways to represent data.

    ```html
    <table>
    </table>
    ```

+ HTML provides `<th>` and `<td>` tags to create a table head and column respectively.

    ```html
    <table>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </table>
    ```

+ HTML provides `<tr>` and `<td>` tags to create a row and column respectively.

    ```html
    <table>
        <tr>
            <td></td>
            <td></td>
        </tr>
    </table>
    ```

+ colspan and rowspan attributes are increasing the span of the cell according to the value specified.

+ `<thead>` and `<tbody>` tags are used to group the heads and body part of the tables.

```html
    <table>
        <thead>
            <tr>
                <th></th>
                <th></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td></td>
                <td></td>
            </tr>
        </tbody>
    </table>
```

## Lists

+ represents related data
+ ordered
+ unordered
+ discription

### ordered list

```html
<ol>
    <li>list 1</li>
    <li>list 2</li>
    <li>list 3</li>
</ol>
```

+ above tags display items with numberings. whis we can change with `type` attributes. predefined alphabets and roman numbers Lowercase and uppercase.

```html
<ol type="a">
    <li>list 1</li>
    <li>list 2</li>
    <li>list 3</li>
</ol>
```

+ We can control the starting point by providing values for `start` attributes.

### unordered list

+ its an unordered bullet list.

```html
<ul>
    <li>list 1</li>
    <li>list 2</li>
    <li>list 3</li>
</ul>
```

+ `type` attributes in unordered list can modify by providing predefined values; disc, circle,square,and none.

### discription list

+ each option with the description list

```html
<dl>
    <dt>description list 1</dt>
    <dl>description</dl>
</dl>
```

## Forms

+ Use for user interaction

### `<form>` tag

+ form is used to wrapped its children `<input>`

+ `action` attribute invoke the url when form will be submitted.

+ `method` attribute has two predefined method `POST` and `GET`. It will defined the type of form method.

+ `novalidate` attribute ignore the validation.

+ `input` modifies providing `type` attributes

+ predefined values are `text`,`submit`,`radio`,`checkbox`,`date`,`email`,`file`,`color`,`number`,`month`, and `time` etc.

+ The `<label>` tag has the information regarding the input.

+ `value` attributes appear in the button text.

+ `checked` attrobute used for checkbox and radio buttons.

+ `disabled` disabled for the users or for certain works.

+ `required` attribute is used for mandatory field.

+ `placeholder` attribute is used as a hint text or guide text.

+ For Example;

```html
    <body>
        <form action="/login.php" method="POST">
            <label>Enter your name</label>
            <input type="text" required>
            <input type="submit" value="Submit">
        </form>
    </body>

```

## Media

+ ### video

+ `<video>` tag is used to display videos in the browser.

+ `controls` attribute provides the basic controlling options.

    + `autoplay` attribute play the video as page loads.

    + `<source src ="path-to-file">` tag define the source of the video

    + `type="video/mp4"` attribute define the type of video.
+ For Example;

```html
    <body>
        <video controls autoplay>
            <source src="videoname.mp4" type = "video/mp4">
        </video>
    </body>

```

+ ### audio

+ define audio on webpage

+ `source` tag defines type and location

+ `controls` attribute provides basic audio controls.

+ `autoplay` automatically play the audio once page loads.

+ For Example;

```html
    <body>
        <audio controls autoplay>
            <source src="audioname.mp4" type = "audio/mpeg">
        </audio>
    </body>

```

## CSS - Cascading Style Sheets

+ css can be used - Externally, Internally, and inline.

+ css finds html element from its selector and applied the value accordingly.

----------------
```css
selector {
  key: value;
}
```

+ Internally  used css example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <style>
      h1 {
        color: white;
      }
    </style>
  </head>
  <body>
    <h1>
      Lorem ipsum,<a
        href="https://google.com"
        target="_blank"
        title="Go to google"
        >dolor</a
      >
      sit amet
    </h1>
  </body>
</html>
```

+ Externally  used css example
  + must written separate file with `.css` extension.
  + must reference using link with attribute `href = name.css` html head section

  ```html

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <title></title>
            <link rel="stylesheet" href="name.css">
        </head>
        <body>
            <h1>
            Lorem ipsum,<a
                href="https://google.com"
                target="_blank"
                title="Go to google"
                >dolor</a
            >
            sit amet
            </h1>
        </body>
    </html>

    ```

+ Inline Css

  + html tags have inline style attribute and directly apply style within tags
  `<p style="color:black;"> inline style attribute.</p>`

+ priority Order ;
  + inline css prioritize than others and among them priority comes internal then external.

+ css selector can be `tag`, `id`, `class` .

+ id can be select using `#idname` sign in css and id name must be unique to other elements

+ class can be select using `.classname` sign in css and same class name can be applied in multiple elements.

+ grouping selector with commas.

+ universal selector `*`.

+ color property can have 3 types of values colorname, HEX value, and RGB value.

+ text-decoration property could have following values : `underline`, `line-through`, `overline`, and `none`.

+ text-align property could have value of horizontal alignment of `left`,`right`,and `center`.

+ font property could have font-family,font-size,style and more.

  + `font-family` property can have value with multiple font name while browser doesn't support prior font.

  + `font-size` can be any of size with the value together in px, em, rem, or %.

  + `font-weight` property set different font weight for the elements.

  + `font-style:italic` to make italic.

### CSS borders, margin, and padding

+ CSS Box Model

+ By default, only content is visible while the border is not and the margin and padding.

  + The content can be text, image, etc.

  + The content is surrounded by the   border.

  + The area between the content and   the border is padding.

  + The area outside the border is   the margin.

  + The border can be visible, depends   on the CSS. But margin and padding are invisible.

+ The content can be text, image, etc.

+ The content is surrounded by the border.

+ The area between the content and the border is padding.

+ The area outside the border is the margin.

+ The border can be visible, depends on the CSS. But margin and padding are invisible.

+ The CSS box model consists of the border, margin, and padding.

+ The border can be set using the "border" shorthand property or properties like "border-width", "border-style", "border-color".

+ The "margin" property is a shorthand property used to set margin in various ways. To set margin for particular directions, use "margin-top", "margin-bottom", "margin-left", or "margin-right".

+ The "padding" property is a shorthand property used to set padding in various ways. To set padding for particular directions, use "padding-top", "padding-bottom", "padding-left", or "padding-right".

### CSS backgrounds

+ change the background color or add an image to the background

+ use the "background-repeat" property and set "no-repeat" as its value

+ use the "background-size" to cover

(Note: footnote from `Web Development for beginner: learn Html/css/javascript step by step.`)
