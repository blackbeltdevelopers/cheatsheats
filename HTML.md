# INDEX
- [Before You learn HTML](#l0)
- [What Is HTML](#l1)
- [A Simple HTML Document](#l2)
- [Basic Elements](#l3)
___
<br><br><br>


# <span id="l0">Before You learn HTML</span>


### Why do you use a web browser?

When you want to go to youtube for example but you don't have their app installed on your pc you go for the browser and access it from there but what happens behind the scenes anyway?

<br>


### Browsers Search Bars

Whatever you type in the search bar and hit enter there are 2 scenarios for it:

1) typing the domain name <br> when you type the domain name of the site you want to visit your browser sends an HTTPS request to the site servers then they send back the HTML code that makes up the home page (or the page you requested) this code gets renderd via the browser rendering engine and thus you get the desired result <br>

2) searching via search engines like Google which is the same process like the first case scenario except that Google searches the web in advance to show you all relevant results for you to choose from

<br>

### REF

_note that there's sth called DNS process that happens in the middle but that's another topic_
<br>
To learn more watch [code.org playlist](https://www.youtube.com/playlist?list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7)

___
<br><br><br>


# <span id="l1">What Is HTML</span>
- HTML is the main language for building websites. You can't have a website without html _even websites builders_ can't do the job without html. In fact you can build a website depending on HTML solely
- HTML stands for Hyper Text Markup Language
    - hyper text is text which contains links to other texts
    - you can think of markup as a way to display text in certain ways like in chat apps we type : \*bold text\* 
- HTML is the standard markup language for creating Web pages
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

