# lab-assignment-1
Base project for lab assignment 1
3.- Explanation of the tags:

Tags:
-html: Defines the start point of a html document.
-head: Here is the metadata of the page and some links.
-meta: Sets the metadata for the page.
-link: It's used to define a link between the html document and an external resource like css or js.
-title: Defines the title of the html document. In our case is "Hacker News".
-body: Defines the body of the page, here is the most of the page definition.
-center: this tag is not suported in html5 but it's used in ycombinator.
-table: In ycombinator, the body is mainly a table. Every news is an element of the table.
-tbody: Is the body of the table,the entire visible page is still inside.
-tr: Defines a row of a table.This tag is used in many forms in this page. The first one is used to set the orange part of the page which has 
another table inside with "a" tags(I will explain this later), td tags, and other tags i will explain ahead.
The second one is used to set the news zone of the page.
The third one is used to set the footer of the page.
In general, is used to place another things, like references to other parts of the site or text 
in different forms, in an ordered way.
-td: As the tr is for the rows in a table, the td tag is for placement of another things in the clomuns of the row.
It is used mainly in the news section.
-a: This tag defines a hyperlink. In this page is mainly used for lead the user to the news that he wants to read.
-span: Is only used to contain a tags.
-script: Is used to load javascript code to the page.

4.- Source files description: 
-(index): Is the reference to the front page of the web site. 
-hn.js: Is a Javascript file that makes the web site dynamic. Also is for loading information asynchronously.
-news.ccc: Is the style of the document. Here its set how the site looks, like its colors, fonts, backgrounds colors, etc...
-.gif files: Those are images(i do not know why they are in gif format) that are placed in the document.

5.- XHR files:
The XHR files are used for HTTP and HTTPS requests to a web server. In ycombinator they aren't used. I mean, if i go to the network.
tab and get the page refreshed(with F5 or Ctrl+F5) they do not show.

6.- Certificate:
emitted by: COMODORO RSA Domain Validation Secure Server CA.
Expiration date: 21-08-2019.