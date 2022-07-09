## <span style="color:green">HTML Notes (Day 4)</span>

### Lets start with wireframing (Because every good web app needs a good base)

* Steps to wireframing
1. Do your research: Figuring out what your planning, even before you plan it out, is a good base to start with.
    * Figure out what you want it to look like. See an awesome website that you want to take some elements from (not plagerizing obviously)? Use that to give yourself the ideas.
    * Figure out what features you want the site to have.
    * What theme do you want to go with? Modern? Classic? Retro? You decide when building the foundation of the site. 
2. Preparing research for quick reference:
    * Build a cheetsheet or a model of your research.
    * Figure out what will work for the website and what wont.
    * More specifically figure out what is "in-scope" and what is "out-of-scope" for the project.
3. Create a flowchart
    * Flowcharts are a great way to visualize your project before diving head first. 
    * Questions like: Where will the user go when they click X link? How will they get back to the homepage? Should this open a new tab? Etc.
4. Draft and sketch, dont design.
    * While design work can be fun it is also a mountain of work, that can be reduced by sketching out the design first rather than illustrating it right away. 
5. Add detail and test
    * This is the part after sketching and drafting where the designing starts.
    * As well as where user tests starts.
    * This is a BAREBONES version of the site. No flashing lights or fireworks, just basic useability.
6. Turn the wireframes into prototypes
    * This is the part where you start laying the groundwork for several design choices to ultimately create that perfect website. 
    * Many may fail, but one will be the one.

### HTML Basics

HTML Stands for *HyperText Markup Language* and consists of varying attributes, elements and tags that make up the basic way websites function and look (on the front end but thats a whole different topic).

*For instance:*

```html
<!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <span style="color:pink">
            <title>Ethan's Amazing Website</title>
            </span>
        </head>
        <body>
            <h2 id="welcome" name="welcome">Welcome to my amazing website</h2>
            <ul>
                <li>Thanks for visiting</li>
            </ul>
        </body> 
    </html>
```
> ## <span style="color:pink">Welcome to my amazing website</span>
>* Thanks for visiting

**Obviously this is a lot more code than markdown for seemingly little effect.**

 - *However*, there is a reason behind this. HTML allows for far more functionality than markdown including text entry, database integration via PHP, SQL and other languages.
- Other features include capability to stylize through languages such as CSS, and even further through Javascript with 3D animations.
- Basically the posibilites are endless, and even though its more code than markdown, HTML gives us the ability to make practically anything a reality on the world wide web.


### A brief description of the code pictured above:
1. The doctype is classifying the file as HTML.
2. The "HTML" tag is used to define the space that the HTML code takes place in.
3. The "head" tag is used to define the header of the webpage.
4. Meta charset is defining the unicode and format of the webpage.
5. The span tag is one of many ways of stylizing a website, with color!
6. The "body" tag is used to define the main body of the webpage.
7. UL stands for unordered list. While LI stands for list. There is also OL for ordered list.
8. Each tag or closing bracket for HTML begins with a / followed by the corresponding tag above.


## whew, thats a lot of information.

*But* thats just the beginning fortunately. As there is so much more to HTML and this single page would turn into tens of thousands with the amount of documentation, creations and overall scale of this programming language. So dive into [MOZILLA's HTML basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics) to get started on your web dev journey.

[Back to main page](README.md)