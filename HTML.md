# INDEX
- [Before You learn web development](#l0)
- [What Is HTML](#l1)
- [Basic HTML page structure](#l2)
- [Basic Elements](#l3)
<!-- - find "later topic" -->
___
<br><br><br>


# <span id="l0">Before You learn web development</span>


## Why do you use a web browser?

When you head for the browser search bar and type in the domain name for the site you wanna visit and hit enter.. What happens behind the scenes?


1) as soon as you hit enter your browser sends a (https) request to the site servers for the data of the web page you enterd its URL

2) the servers respond and send back the data for the target page _and this data which is HTML code_ makes up the web page

3) the rendering engine of the browser renders HTML code and thus you get your desired page 

<br>

## We'll learn how to build websites using HTML

<br>

## REF:

_note that there's sth called DNS process that happens in the middle but that's another topic_
<br>
To learn more watch [code.org playlist](https://www.youtube.com/playlist?list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7)

___
<br><br><br>


# <span id="l1">What Is HTML</span>
- HTML is the main language for building websites. You can't have a website without html _even websites builders_ can't do the job without html. In fact you can build a website depending on HTML solely and thus HTML is the standard markup language for web pages

- HTML stands for Hyper Text Markup Language
    - hyper text is text which contains links to other texts
    - you can think of markup as a way to display text in certain ways like in chat apps we type : \*bold text\*

- It consists of series of elements that tell the browser how to display the content

- _Of Course HTML does more than just showing text (and that's the fun part)_
<br><br>
## HTML elements in a nutshell :
<span id="html-element">![HTML elements in a nutshell](https://raw.githubusercontent.com/blackbeltdevelopers/cheatsheats/main/assets/md-pics/html-element.jpg)</span>
___
<br><br><br>

# <span id="l2">Basic HTMl page structure</span>
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>...</title>
    </head>
    <body>
        <p>this is normal text displayed on the page</p>
    </body>
</html>
```
## DOCTYPE
- Doctype stands for Document Type Declaration

- It informs the web browser about the type and version of HTML used in building the web document

- This helps the browser to handle and load it properly

- Each version of HTML has its own rules. The example above is for HTML5
<br>

## html _tag_

- All web pages start with the html element As it's used as a container for all of the HTML of an entire document.

- It’s also called the root element because it’s at the root of the elements tree that makes up a web page

- Usage: structural
<br>

## head

- It's a container for metadata (later topic but for now it's known as "data about data")

- Anything that goes inside the head element is not displayed on the page
<br>

## title

- Want to give your web page a custom "title"? simple just use the "title" tag

- this is the page (browser tab) title
<br>

## body

- it defines the document body which is..

- A container for all the visible contents, such as headings (like h1), paragraphs (like p), images, hyperlinks (links), etc
<br>

## p

- just a simple tag for holding text in an organized way which can be stylized later using _CSS_ (like changing the color)

- most browsers display paragraphs with a vertical gap between each paragraph, nicely breaking up the text.
<br>

## now take note

- hrml tags does not get displayed on the page but rather tells the browser information how to display the text and that's what a markup language does

- in the past a writer would for example underline a word to tell the printing agency that this word is to be printed italic

- html tags has other information too other than the render style
<br>

## Structure Visualization
![](https://raw.githubusercontent.com/blackbeltdevelopers/cheatsheats/main/assets/md-pics/basic-html-page-Visualization.jpg)
___
<br><br><br>

# <span id="l3">Basic Elements</span>
- [html, head, title, body, p](#html-blah)
- [headings](#section-headings)
- [div](#div)
- [span](#span)
- [links](#links)
    - [href values (URLs in general : absolute vs relative)](#urls-in-general)
    - [target values](#target-values)
    - [Internal Links](#internal-links)
- [images](#img)

<br>

## first understand block-level and inline elements

- Block-level elements, such as [div](#div), [h1](#section-headings), and p, are elements that are designed to hold relatively large or stand-alone blocks of content, such as paragraphs of text

-  A block-level element always starts on a new line

- Inline elements, such as [span](#span), [a](#links), and img, are designed to hold smaller pieces of content — such as a few words or a sentence — within a larger block of content

- Adding an inline element doesn’t cause a new line to be created

- Block-level elements can contain inline elements, but inline elements can’t contain 
<br>

## <span id="html-blah">html, head, title, body, p</span>

We've already discuess those elements in [Basic HTMl page structure](#l2) section
<br>

## <span id="section-headings">h1~h6 _aka section headings_</span>

- Headings let you break up your page content into readable chunks. They work much like headings and subheadings in a book or a report

- h1 is written only once in the page according to layouts standars which is the hero text _(later topic)_

- typically you won’t need to use more than h1, h2 and h3, unless your page is very long and complex

- as a challenge (simple one ofc lol) give it a try and write some headings elements (or all the six ones!) and see how it will look on your browser [_for a refresher look up the image_](#html-element)
<br>

## <span id="div">div</span>
- Document "__div__ ision" 
- A block-level generic container that you can use to add more structure to your page content. For example, you might group several paragraphs or headings that serve a similar purpose together inside a div element. Typically, div elements are used for things like:
    - Page headers and footers
    - Columns of content and sidebars
    - Highlighted boxes within the text flow
    - Areas of the page with a specific purpose, such as ad spots
    - Image galleries
<br>

## <span id="span">span</span>
- An inline container for content &nbsp; (we'll discuss inline and block-level elements in a later topic but for now think of span as way to select a certain word or more in a paragraph for styling or other purposes)

- The span element is similar to div in that it’s used to add structure to your content. The difference is that div is a block-level element, while span is an inline element:
<br>

## <span id="links">links _(a/ anchor element)_</span>

there are 3 things you need to know

- the a tag which stands for "anchor" &nbsp;&nbsp;&nbsp; _\<a>\</a>_
- href attribute which stands for "Hypertext Reference" &nbsp;&nbsp;&nbsp; _href=""_
    - here you put the URL like "https://www.google.com"
    - 
- target attribute &nbsp;&nbsp;&nbsp; _target=""_
    - one of its values is "blank" which opens the link in a new tab
    - you can use "self" if you want to open the link in the same page

<br>

### putting it all together

```HTML
<a href="https://www.google.com" target="blank">
     Google
</a>
``` 

<br>

### <span id="urls-in-general">href values _(URLs in general : absolute vs relative)_</span>

- Absolute paths contain a complete URL (fully qualified), which includes a protocol, the website's domain name and possibly a specific file, subfolder, or page name. For example:
```html
<a href="https://trends.google.com/trends/">Google Trends</a>
```

- Relative links only include the name of a specific file or page, which is relative, to the current path. If you keep all of your website's files in a single directory, you can establish links between pages as follows:
```html
<a href="file.pdf">Next page</a>
```

- _NOTICE that writing the file extension is a MUST!_
    - if the extension is not shown right click on the file then view it from the properties tab

- In the case above, the link is only valid within the directory that page2.html is located. When clicked, the browser searches the current page's directory for page2.html and displays it.

- NOTE : file names and folders must be written exactly as it is (case sensitive) like the fact that "File.pdf" and "file.pdf" are completely different files

- if the file is in another folder in the same directory and the folder is in the same level as the html file:
```html
<a href="folder2/file.pdf">Next page</a>
```

- if you wanna link to a file (like file.pdf) that's in a higher directory for example :
    - the html file location is "projects/website/index.html"
    - and the file.pdf location is "projects/file.pdf"
    - you'd write it like so :
```html
<a href="../file.pdf">Previous Page</a>
```

- but what if you need move up and then move down?
    - the html file location is "projects/website/index.html"
    - and the file.pdf location is "projects/books/file.pdf"
    - [Visualization](#move-up-then-down)
    - you'd write it like so :
```html
<a href="../books/file.pdf">Previous Page</a>
```

<span id="move-up-then-down">

![](https://raw.githubusercontent.com/blackbeltdevelopers/cheatsheats/main/assets/md-pics/move-up-then-down.jpg)

</span>

<br>

### <span id="target-values">target values : "blank" vs "_blank"</span>

- Using "blank" will open your link in a new tab/window.
- However, Clicking on the link again will reuse the window that was opened the first time instead of opening a new one _like this:_

![](https://raw.githubusercontent.com/blackbeltdevelopers/cheatsheats/main/assets/md-pics/target-attr-0.gif)

- Unlike "_blank" no matter how many times you click on the link a new tab will always open _like. this:_

![](https://raw.githubusercontent.com/blackbeltdevelopers/cheatsheats/main/assets/md-pics/target-attr-1.gif)

<br>

### <span id="internal-links">Internal Links</span>

Just like the index links and othre internal links I've made in this md file I'm using a similiar syntax like that of html. So how do we do it?
 - First : you give an id value _(the id attr)_ to the element that you want to reference to like so :
```html
<div id="container"></div>
```

 - Second : you write an a element (anchor element)
    - you write the id of the target element as the href value
    - _BUT_ &nbsp; a # sign first like so :
```html
<a href="#container">go to the container element</a>
```

- of course there's no need to use target attr here, buddy! hehe:)

<br>

## <span id="img">images _(img element)_</span>

much like how anchor element link works except for a few differences
```html
<img src="me-and-my-friends.png" alt="Me and My friends">
```

- NOTICE : it's better not to use spaces when naming files as spaces are encoded by the server, producing long, ugly URLs. Use hyphens instead. for more info : [file naming conventions](https://josephpinder.com/blog/file-naming-conventions-for-web-developers) 

- src attr : the same as [href](#urls-in-general) but instead of the absolute url of a page you write the url of the image itself like this:
    ```
    https://raw.githubusercontent.com/blackbeltdevelopers/cheatsheats/main/assets/md-pics/move-up-then-down.jpg
    ```

- alt attr : 
    - the value/ text you write in gets shown when for whatever reason the image can't be loaded like &nbsp; 404 &nbsp; if you're using an image from another website and that website removed it from their servers
    - it's also useful for SEO (search enginge optimaization) when search eninges scan the web
    - SO NEVER OMIT THE "alt" ATTRIBUTE!
