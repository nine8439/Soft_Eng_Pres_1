#HTML Presentation
##History of HTML
	+ Web Invented with HTML with HTML as its Publishing Language

    + In 1980, physicist Tim Berners-Lee, who was a contractor at CERN, proposed and prototyped ENQUIRE, a system for CERN researchers to use and share documents.

    + Berners-Lee specified HTML and wrote the browser and server software in late 1990.


##HTML

	+HTML stands for Hyper Text Markup Language

	+The markup language is used for describing web documents

	+The language is built up using a set of markup tags

	+HTML documents are described by HTML tags, and each tag describes a different document type

    +HTML is not case sensitive

    +HTML documents contain HTML tags and plain text

    +A tag is always enclosed in an angle bracket, (i.e. <>, <HTML>)

    +Tags usually come pairs, start tag and end tag or opening tag and closing tag, where the closing

    +tag will usually begin with /, (i.e. <HTML>...</HTML>)

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


    1. The first tag indicates that the document type will be HTML

    2. The text between <html> and </html> describes an HTML document

    3. The text between <head> and </head> provides information about the document

    4. The text between <title> and </title> provides a title for the document

    5. The text between <body> and </body> describes the visible page content

    6. The text between h1 and /h1 describes a heading

    7. The text between <p> and </p> describes a paragraph


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
    + HTML documents are divided into paragraphs
    
    + Paragraphs are defined by the <p> tag

    + You cannot be sure how HTML will be displayed.
    
    + Large or small screens, and resized windows will create different results.

    + With HTML, you cannot change the output by adding extra spaces or extra lines in your HTML code.

    + The browser will remove extra spaces and extra lines when the page is displayed.

    + Any number of spaces, and any number of new lines, count as only one space

    + If you would like the text to display as the programmer formatted it, then the tag <pre> should be employed. The content will be dsiplayed as its formatted in between the start and end tag

    ~See the examples folder to see different formattings and how they are treated in HTML



<h3>Line Breaks</h3>
    <br> Will start a new line without starting a new paragraph
    <hr> Will create a horizontal line 

<h3>Text Formatting Tags</h3>
    + <b> Defines bold text

    + <big> Defines big text

    + <em> Defines emphasized text

    + <i> Defines Italic text
    
    + <small> Defines small text

    + <strong> Defines strong text
    
    + <sub> Defines subscripted text

    + <super> Defines superscripted text
    
    + <ins> Defines inserted text

    + <del> Defines deleted text

    + <tt> Defines teletype text

    + <u> Defines underline text

    + <strike> Defines strike text
    
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

| Target Value   | Description   |
| -------------  |:-------------:|
| _blank         | Opens the linked document in a new window or tab                                     |
| _self          | Opens the linked document in the same frame as it was clicked (this is default)      |
| _parent        | Opens the linked document in the parent frame                                        |
|_top            | Opens the linked document in the full body of the window                             |
|<i>framename</i>| Opens the linked document in a named frame                                           |


<h3>Images</h3>

    + To display an image on a page, you use the image tag, as well as the source attribute which specifies where the image is stored
    (i.e. <Img SRC="Desktop/Photos/Photo.jpeg">)
    
    <h4>Image attributes</h4>
        + <img> Defines an image
        + <Src> Display an image on a page, Src is the source of where the image is stored. A url can also be a source
        + <Width> Defines the width of an image
        + <Height> Defines the height of the image
        + <Border> Defines a border of the image
        + <Hspace> Horizontal space of the image
        + <Vspace> Vertical space of the image
        + <Align> Align an image within the text
    
<h3>Tables</h3>
    Tables are defined with the <table> tag
    Tables are divided into table rows with the <tr> tag.
    Table rows are divided into table data with the <td> tag.
    A table row can also be divided into table headings with the <th> tag.

    Other Table Attributes
        + <Caption> captions the table

        + <colgroup> defines the groups of table columns
    
        + <col> Defines the attribute values for one or more columns in a table

        + <thead> Defines a table head
    
        + <tbody> Defines a table body
    
        + <tfoot> Defines a table footer
    
        + <CellSpacing> amount of spaces between table cells
    
        + <Colspan> space around the edges of each cell
        
<h3>List Tag</h3>

    <b>Unordered lists</b> : unordered list are bulleted 
    <b>Ordered Lists</b> : Ordered Lists are numbered
    <b>Definition Lists</b> : Used to create a definition list
    
    + <LI> empty tag, used for representing list terms
    
    + <OL> Ordered List
    
    + <UL> Unordered List
    
    + <DL> Defines a definition list
    
    + <DT> Defines a term in a definition list
    + <DD> Defines a description of a term in a definition list
    
<h3>Forms</h3>

    ~A form is an area that can contain form elements
    ~Form elements are elements that allow the user to enter information in a form, such as
    text fields, text area fields, drop-down menus, radio buttons, checkboxes, and etc.
    ~A form tag is used to define a form, <form>
    <form>
    .
    input
    .
    </form>

    More tags that can be used in forms
        + <form> Defines a form for user input

        + <input> used to create an input field
    
        + <text> Creates a single line text entry field
    
        + <textarea> Defines a text area
    
        + <password> Creates a single line text entry field. The characters entered appear as asterisks (*)
    
        + <label> Defines a selectable list

<h3>Developing HTML</h3>

    Writing the Code
        ~Any text editor should suffice for writing html code. Any file should be saved with the .html extension
    Running the Code
        ~Save the HTML file
        ~Open an internet browser and input the file path into the URL Bar, or Address Bar, and hit enter

<h3>HTML and Software Engineering</h3>

    + HTML is used by 65.3% of all the websites whose markup language we know.

    + In web application development, HTML usually provides the front end and user interface aspects 
    
    + HTML can interact with many languages on the back end
        1. This means HTML can pass data and information it receives on the front end, and pass it to a a method running a 
            different language which contains the logic of the application

        2. Example of Languages that HTML interfaces well with: Go, Node.js, Python/Ruby, Java, C#

        <h4>How they interact with HTML</h4>

        1. Java: Chosen by big players. It doesn’t mean that Java is the best one. Java was built around Enterprise model. At the beginning they planed to make business around it (the same .NET). It means that Java is: reliable, expensive. The costs come with overcomplicated solutions. But it also means that they are overestimated. Just check how popular web framework are going. Which startup is using Enteprise now? It’s complicated. Sprigs goes towards Rails model now (and still doesn’t have WebSockets support). Leading companies, which want to have Java stack, prefer new fresh solutions (Play, Scala etc...) - LinkedIn, Xerox. Google have their own solutions. Oracle? They took open MySQL and almost close it. Just look how they did with 5.6 release.

        2. Python/Ruby: Very fast developing and prototyping. Enjoy when coding, easy to maintain and refactor. Most of the web is driven by Python / Ruby / PHP frameworks (I don’t want to talk about the last one). Those languages are built by professional geeks. 
    
            Disadvantage: not as fast as Java. But for serving web content it is fast enough. Because there are implementations with JIT (eg PyPy, Numba for Python), this disadvantage is going to be even weaker. JIT gives a huge boost.

            Others also can argue that dynamic type languages (like Python, Ruby) are error prone. Static types allows you to find bugs earlier, but only some of them. If want to rely on static type checking, then I feel sorry for your applications and developers. All in all you need to have tests that cover all functions. Those tests, by the way, make validations about arguments (types) you pass to functions. On the other hand Java type hierarchy slows your development and makes refactoring hard.

        3. Node.js: Similar to Python/Ruby, offers better performance rather than reliability

        4. Go:  Takes the best from Java (fast) and Python / Ruby (fun, productive). Have simple yet powerful type hierarchy. Disadvantages: although the project is stable, there are not a lot of tools around it. Some which exists are not as rich / mature as the ones we have in previous technologies.
            Nonetheless Go is already used in production (Google, Heroku). 
    
        5. C#: For many, C# has a familiar syntax in that it follows C.
        Fully integrated with the .NET library, providing access to a great repository of functionality and support.
        Safer than its namesakes (C/++) in that pointer types are not permitted. Loses any cross-platform capabilities because of the integration with .NET.

    
<h3>Learn more about HTML</h3>

~The internet is a great resource for learning HTML:
1. Youtube video which gives good overview on how to get started: <a href="https://www.youtube.com/watch?v=fS7w-TXinPE">https://www.youtube.com/watch?v=fS7w-TXinPE</a>
2. This website provides a reference with examples for many HTML questions: <a href="http://www.w3schools.com/html/">http://www.w3schools.com/html/</a>

<h3>Examples</h3>
Head over to the example folder in the repository to see example of all the topics discussed.

They can be run as described earlier in the presentation
        






        
