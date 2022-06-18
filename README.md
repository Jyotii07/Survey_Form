# Survey_Form

Q 1) What is HTML ??
:- HTML stands for Hypertext Markup Language.
:- It is used to create struture of     webpages that are displayed on the Browser or World wide web(www).
:- and It contains Tags and Attributes that are used to design the web pages. Also , We can link multiple pages using the Hyperlinks.
:- with HTML you can create your own Website.
:- Html Elementwraps all the content on the entire page.
:- It is also known as the ROOT element . 

Note :

1) Hypertext :- it is a word that contain a link to a website.
ex:- "Facebook" is a word that links to the Facebook page.

2) Markup Language :- it is a Computer Language that uses tags to define elements within a document.

Q 2) What is DocType HTML ??
:- A Doctype is Document Type Declaration (DTD) . It is an instruction that tells the web browser about the version and which the current page is written.
:- It is not an element or tags.
:- It is case-insensitive. (it doesn't mind whether alphabet in lower case or upper case it return true if alphabet is right only. )
:- The Doctype declaration appears at the top of a web page before all other elements .

:- In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.

Q 3)What is head ??
:- This is element acts as container for all stuff you want to include Title , Link CSS's external link, character set declarations and more.


Q 4) What about BODY tag ?
:-  This tag contains all the content that you want to show to web users they visit your page, whather that's text, images, videos , games, audios, or whatever else.

Q 5) Link ?
:- The <link> tag defines the relationship between the current document and an external resource.
:- The <link> tag is most often used to link to external style sheets or to add a favicon to your website.
:- The <link> element is an empty element, it contains attributes only.
:- most common attribue like :
1. href = Specifies the location of the linked document.

2. rel = Required. Specifies the relationship between the current document and the linked document.

3. type = Specifies the media type of the linked document.


Q 6) Anchor tag??
:- Link are very important tag to link other file as a text .
:- we need to use a simple element <a>.
:- "a" being the short form for "anchor".
:- You have to use "href" attribute with the address that yow want to link .
:- we link n number of file in our page.



Q 7) Image tag?
:- It set the image into our webpage using src(source) attribute, which contains the path to our image file.
:- We have alt (alternative) attribute.
in this attribute , you specify Image in text for users who cannot see the image , due to any reason.


Q 8) P tag??
:- The <p> tag defines a paragraph. Browsers automatically add a single blank line before and after each <p> element. 
:- By default, the display of the Paragraph element is set to “block” which you can change using CSS. This means that if you add another paragraph to the webpage the next paragraph will be inserted in the next line on the webpage.


Q 9) Form ??
:- The <form> tag is used to create an HTML form for user input.
:- the form will take input from the form and post that data in backend applications (like PHP). 
:- There are various form elements that we can use like text fields, text area, drop-down list, select, checkboxes, radio, etc.
:- There are many attributes that are associated with the <form> tag.
like 
1) Action :- This is used to send the data to the server after the submission of the form.
2) Method :- This is used to upload the data by using two methods that are Get and Post.
Get Method: -It has a limited length of characters of URL. -we should not use get to send some sensitive data. -This method is better for non-secure data.

Post Method: -1. It has no size limitations . The submission of the form with the method post, can not be bookmarked.

3) Enctype :- This attribute is used to specify that how a browser decodes the data before it sends it to the server .so the values of this attribute are: -1.application/x-www-form-urlencoded − It is the standard method most forms used 2.multipart/form-data -it is used when you have something to upload like files of images, word files, etc.



Q 10) Table ??
:- HTML table tag is used to display data in tabular form (row * column). There can be many columns in a row.
:- We can create a table to display data in tabular form, using <table> element, with the help of <tr> , <td>, and <th> elements.
:- In Each table, table row is defined by <tr> tag, table header is defined by <th>, and table data is defined by <td> tags.

colspan
:- If you want to make a cell span more than one column, you can use the colspan attribute.
:- If you want to make a cell span more than one column, you can use the colspan attribute.

rowspan
:- If you want to make a cell span more than one row, you can use the rowspan attribute.
:- It will divide a cell into multiple rows. The number of divided rows will depend on rowspan values.



Q 11) List ??
:- This is used for Marking or specifying  Lists of Information. 
:- there are three ways but mostly used 2.
:- 1. Ordered list and 2. Unoredered list 3. Definition Lists
 

Ordered list 
:= This will describe as a numbers formate. 
:= this list is created by using <ol> tag.
:= and we can use type attribute for <ol> tag to specify the type of numbering you like. which means "A" ,"a" , "I" , "i".
:= By default value is "number".
:= You can use start attribute for <ol> tag to specify the starting point of numbering you need.

ex:=
<ol type = "1" start = "4"> - Numerals starts with 4.
<ol type = "I" start = "4"> - Numerals starts with IV.
<ol type = "i" start = "4"> - Numerals starts with iv.
<ol type = "a" start = "4"> - Letters starts with d.
<ol type = "A" start = "4"> - Letters starts with D.

Unordered List 
:= An unordered list is a collection of related items that have no special order or sequence.
:= This list is created by using HTML <ul> tag . Each item in the list is marked with a bullet.
:= You can use "type" attribute for <ul> tag to specify the type of bullet you like.
:= By default, it is a disc.
 ex:= 
 <ul type = "square">
<ul type = "disc">
<ul type = "circle">

Definition List
:= HTML and XHTML supports a list style which is called definition lists where entries are listed like in a dictionary.
:=  The definition list is the ideal way to present a glossary, list of terms, or other name/value list.

Definition List makes use of following three tags.

<dl> − Defines the start of the list
<dt> − A term
<dd> − Term definition
</dl> − Defines the end of the list.



Q 12) Attribute , Tag and Element ??
:=  All HTML elements have attributes that will provide additional information about that particular element. 
:- It takes 2 parameters, ie, a name & a value which define the properties of the element and are placed inside the element tag.
:- Every name has some value that must be written within quotes.

ex: src, href, width, height , id  etc.

Tag 
:- HTML tags are like keywords which defines that how web browser will format and display the content.
:-  HTML tags contain three main parts: opening tag, content and closing tag. But some HTML tags are unclosed tags.
:- An HTML file must have some essential tags so that web browser can differentiate between a simple text and HTML text.

Unclosed HTML Tags
:- Some HTML tags are not closed, for example br and hr.
<br> Tag: br stands for break line, it breaks the line of the code.
<hr> Tag: hr stands for Horizontal Rule. This tag is used to put a line across the webpage.

Element
:- An HTML element is the collection of start and end tags with the content inserted in between them.
:- The HTML element is use inside the another HTML Element is called nested HTML elements.
:- <html> tag contains the <head> and <body>. The <head> and <body> tag contains another elements so it is called nested element.
:- HTML Elements without any content i.e, that do not print anything are called "Empty elements". Empty HTML elements do not have an ending tag. For instance. <br>, <hr>, <link>, <input> etc are HTML elements.


(tag
element
attribute)
----------------------------------------
HTML tags are used to hold the HTML element.
HTML element holds the content.
HTML attributes are used to describe the characteristic of an HTML element in detail.
*************
HTML tag starts with < and ends with >
Whatever written within a HTML tag are HTML elements.
HTML attributes are found only in the starting tag.
*************
HTML tags are almost like keywords where every single tag has unique meaning.
HTML elements specifies the general content
HTML attributes specify various additional properties to the existing HTML element.

-------------------------------------------




Q 13) Headings???
:- We have 6 heading levels. H1 to h6
:- Heading tags allow you to specify the title or heading or subheadings. 
:- H1 is used for most important heading. whether
:- H6 is used for least important heading .

Q 14) Semantic Element ??
:- A semantic element clearly describes its meaning to both the browser and the developer.
:- Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.
:-  Examples of semantic elements: <form> , <table> , and <article> - Clearly defines its content.
