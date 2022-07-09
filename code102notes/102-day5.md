## CSS Notes (Day 5)

CSS, at its core, is how you stylize an HTML webpage. It can do everything from color to pixel-perfect margins and borders. However, there is a lot to unpack with CSS as there are hundreds of different ways to use it to style a webpage, and no one way is going to be the same. Basically, to use CSS to its full potential, one must consider what they want to style and how. Because without a wireframe/design in place, CSS is basically pointless.

*However*, after a wireframe and design are created, you can get to work matching those in CSS.

### Here is a basic cheatsheet to CSS:

**Linking a CSS stylesheet to an HTML file**

If the CSS stylesheet is in the same location as the HTML file:

```HTML
<link rel="stylesheet" href="style.css">
<!-- Put this tag in your <head> part of the HTML file -->
```


```CSS
tag {
    /* This is your space to define what a specific HTML tag should look like.
    Additionally, a comment is created with the opening and closing asterisk and backslash. */
}
```
```CSS
/* There are several defining elements in each tag bracket, but here are the main ones: */
/* Please note, all fonts, colors, and arguments are just examples. */
tag {
    background-color: #8b8b8b;
    font-family: 'Times New Roman', Times, serif; 
    padding: 0;
    margin: 0;
    list-style: none;
    height: 100px;
    float: left;
    margin-left: 50px;
    margin-right: 50px;
    color: #EEEEEE;
    display: inline-block;
    text-align: center;
    text-decoration: none;
    font-weight: 600;
    font-size: 20px;
    /* This next one changes your cursor, mostly used if hovering over something like a link */
    cursor: pointer;
    width: 0px;
    height: 0px;
    border: 10px;
    border-radius: 25px;
    position: center;
    /* Please note that these are some of many different style options in CSS */
}
```

**There are also ways to define tags by a id or class name**

Firstly, to define a class or id in html:

```HTML
<p id="id_name">This is how you add an ID to a tag</p>
<p class="class_name">This is how you add a class to a tag</p>
```

To then call on that id or class in CSS:

```CSS
#id_name {
    /* This is how you style a specific ID */
}
.class_name {
    /* This is how you style a specific class */
}
```

[Back to main page](README.md)