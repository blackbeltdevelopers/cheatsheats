# INDEX
- [Before You learn web development](#l0)
- [What Is HTML](#l1)
- [A Simple HTML Document](#l2)
- [Basic Elements](#l3)
___
<br><br><br>


# <span id="l0">Before You learn web development</span>


### Why do you use a web browser?

When you head for the browser search bar and type in the domain name for the site you wanna visit and hit enter.. What happens behind the scenes?

<br>

1) as soon as you hit enter your browser sends a (https) request to the site servers for the data of the web page you enterd its URL

2) the servers respond and send back the data for the target page _and this data which is HTML code_ makes up the web page

3) the rendering engine of the browser renders HTML code and thus you get your desired page 

### We'll learn how to build websites using HTML

<br>

### REF:

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
### HTML elements in a nutshell :
![HTML elements in a nutshell](https://raw.githubusercontent.com/blackbeltdevelopers/cheatsheats/main/assets/md-pics/html-element.jpg)
___
<br><br><br>

# <span id="l2">A Simple HTML Document</span>
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Awesome Title</title>
    </head>
    <body>
        <h1>I love html</h1>
        <p>Not creative I know XD</p>
    </body>
</html>
```
### DOCTYPE
- Doctype stands for Document Type Declaration
- It informs the web browser about the type and version of HTML used in building the web document
- This helps the browser to handle and load it properly
- Each version of HTML has its own rules. The example above is for HTML5
<br>

### html _tag_

- All web pages start with the html element
- It’s also called the root element because it’s at the root of the tree of elements that make up a web page
<br>

### head

- It's a container for metadata (data about data)
- Anything that goes inside the head element is not displayed on the page
- the title element inside is for the page (browser tab) title
<br>

### body

- it defines the document body which is..
- A container for all the visible contents, such as headings (like h1), paragraphs (like p), images, hyperlinks (links), etc
<br>

### now take note

- hrml tags does not get displayed on the page but rather tells the browser information how to display the text and that's what a markup language does
- in the past a writer would for example underline a word to tell the printing agency that this word is to be printed italic
- html tags has other information too other than the render style
<br>

### Structure Visualization

- node tree
- w3
___
<br><br><br>

# <span id="l3">Basic Elements</span>

### links

- external
```HTML
<a href="https://www.youtube.com/channel/UC4tEB93QVPiiFWasqEhO7_A" target="_blank">
     BlackBelters
</a>
```

