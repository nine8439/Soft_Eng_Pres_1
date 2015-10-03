#HTML Presentation
##History of HTML
	###Web Invented with HTML with HTML as its Publishing Language
		In 1980, physicist Tim Berners-Lee, who was a contractor at CERN, proposed and prototyped ENQUIRE, a system for CERN researchers to use and share documents.
		Berners-Lee specified HTML and wrote the browser and server software in late 1990.


##HTML
	HTML stands for Hyper Text Markup Language
	The markup language is used for describing web documents
	The language is built up using a set of markup tags
	HTML documents are described by HTML tags, and each tag describes a different document type
    HTML is not case sensitive
    HTML documents contain HTML tags and plain text
    A tag is always enclosed in an angle bracket, (i.e. <>, <HTML>)
    Tags usually come pairs, start tag and end tag or opening tag and closing tag, where the closing
    tag will usually begin with /, (i.e. <HTML>...</HTML>)

    Simple HTML example
        <!DOCTYPE html>
        <html>
        <head>
        <title>Page Title</title>
        </head>
        <body>

        <h1>My First Heading</h1>
        <p>My first paragraph.</p>

        </body>
        </html>

    ~The first tag indicates that the document type will be HTML
    ~The text between <html> and </html> describes an HTML document
    ~The text between <head> and </head> provides information about the document
    ~The text between <title> and </title> provides a title for the document
    ~The text between <body> and </body> describes the visible page content
    ~The text between <h1> and </h1> describes a heading
    ~The text between <p> and </p> describes a paragraph

##HTML Tags
    Container Element
        ~Container Tags contains a start and end tag, (i.e. <p>...</p>)
    Empty Element
        ~Tags which only require start tag, (i.e. <br> which starts a new line)
    Heading Element
        ~Prints the heading of the page, ranges from <H1> to <H6>. <H1> prints the 
        largest heading and <h6> prints the smallest heading
        ~Heading tags also require end tag
        The following tags begin with <h1> tags and increase to <h6> tags

        <html>
        <head><title>heading example</title></head>
        <body>
        <h1>Header 1</h1>
        <h2>Header 2</h2>
        <h3>Header 3</h3>
        <h4>Header 4</h4>
        <h5>Header 5</h5>
        <h6>Header 6</h6>
        </body>
        </html>

<h3>Paragraph tag</h3>
    HTML documents are divided into paragraphs
    Paragraphs are defined by the <p> tag
    You cannot be sure how HTML will be displayed.
    Large or small screens, and resized windows will create different results.
    With HTML, you cannot change the output by adding extra spaces or extra lines in your HTML code.
    The browser will remove extra spaces and extra lines when the page is displayed.
    Any number of spaces, and any number of new lines, count as only one space
    If you would like the text to display as the programmer formatted it, then
    the tag <pre> should be employed. The content will be dsiplayed as its formatted in between the start and end tag
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser 
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser 
ignores it.
</p>

<pre>
My Bonnie lies over the ocean.

My Bonnie lies over the sea.

My Bonnie lies over the ocean.

Oh, bring back my Bonnie to me.
</pre>

<h3>Line Breaks</h3>
    <br> Will start a new line without starting a new paragraph
    <hr> Will create a horizontal line 

<h3>Text Formatting Tags</h3>
    <b> Defines bold text
    <big> Defines big text
    <em> Defines emphasized text
    <i> Defines Italic text
    <small> Defines small text
    <strong> Defines strong text
    <sub> Defines subscripted text
    <super> Defines superscripted text
    <ins> Defines inserted text
    <del> Defines deleted text
    <tt> Defines teletype text
    <u> Defines underline text
    <strike> Defines strike text
    
Examples:

<p>This text is normal.</p>

<p><b>This text is bold</b>.</p>

<p><strong>This text is strong</strong>.</p>

<p><i>This text is italic</i>.</p>

<p><em>This text is emphasized</em>.</p>

<p>This is <sup>superscripted</sup> text.</p>

<p>This is <sub>subscripted</sub> text.</p>

<h3>Background and text color</h3>
    The attribute bgcolor can set the color of the background on a page, (i.e. <body bgcolor = "Red">)
    The text tag can be used to change the text color, (i.e. <body texts = "Red">)

<h3>Text Allignment</h3>

    Like any ohter document, you can have the text centered, aligned right, or aligned left. The following commands are as follows
    <align = "left">
    <align = "center">
    <align = "center">
    
<h3>Hyperlink Tag</h3>
A hyperlink is a text or an image you can click on, and jump to another document.
In HTML, links are defined with the <a> tag:
    <a href="url">link text</a>

Within a link, you can add a target attribute. The target attribute specifies where to open the linked document.

| Tables         | Are           |
| -------------  |:-------------:|
| _blank         | Opens the linked document in a new window or tab                                     |
| _self          | Opens the linked document in the same frame as it was clicked (this is default)      |
| _parent        | Opens the linked document in the parent frame                                        |
|_top            | Opens the linked document in the full body of the window                             |
|<i>framename</i>| Opens the linked document in a named frame                                           |







        
