# lab-assignment-1

## 1. Elements tab
### HN's DOM as a general tree looks as follows:
```
html
├──  head
|   ├── meta
|   ├── link
|   └── title
└── _body
    ├── _center
    |   └── _table
    |   	└── _tbody
    |   		├── _tr
    |   			├── _td
    |   		    	└── _td
    |   		├── _tr 
    |            ...
    └── script

```
### Tags description
- `<html> .. <\html>`: Marks the start and end of the html document.
- `<head> .. <\head>`: Marks the start and end of the document's head. Contains metadata (document's title, links, scripts to be loaded before the body, char set, etc...)
- `<meta> .. <\meta>`: To specify metadata like the document's autor, description, etc...
- `<link> .. <\link>`: To link the document to external resources like CSS, page icon, etc.
- `<title> .. <\title>`: Document's tile, usually shown in the browser's window title bar. 
- `<body> .. <\body>`: Marks the start and end of the document's body.
- `<center> .. <\center>`: A deprecated tag to tell the renderer that it's content should be centered in the page.
- `<table> .. <\table>`: Start/end of a table.
- `<tbody> .. <\tbody>`: Groups the table's body content
- `<tr> .. <\tr>`: A table's row.
- `<th> .. <\h>`: A table's header.
- `<td> .. <\td>`: A table's data.
- `<a> .. <\a>`: Link. Can specify destination with the `href` attribute.
- `<div> .. <\div>`: Block element with no meaning that can wrap something and asign it a class, id, etc...
- `<span> .. <\span>`: Inline element with no meaning that can wrap something and asign it a class, id, etc...
- `<script> .. <\script>`: Loads a script (usually js) from a source or inbody. Its position in the document determines  when it will be loaded.
- `<img> .. <\img>`: Loads an image.
- `<br>`: A line break.
- `<form> .. <\form>`: Start/end of a form used to collec data to some purpouse.
- `<input> .. <\input>`: Recieves input from the user. It can be text, a selected or not checkbox, ect...

## 2. Sources tab
Internal / external files requested by the HTML. In this case:
- news.css: CSS file that defines the styling used in the document.
- hn.js: JavaScript called to modify/control the DOM. For example, when a user gives an upvote to an article, this script handles that input and send it to the server to be processed.
- grayarrow.gif: Upvote arrow image.
- y18.gif: Y Combinator's logo, shown in the upper bar.
- s.gif: Transparent 1x1 px image used as a separator.

## 3. Network tab
### XHR (XMLHttpRequest)
XMLHttpRequest is an API provided by all major web browsers which allows the borwser to comunicate with a server, transfering data as XML, Json, plain text, etc...
For example, Ajax makes use of this API to send and recieve data asynchronously, without the need to reload the page, making modifications of the DOM acordingly if necessary.

### At what moment were these files loaded by the web browser?
In the order of appearence in the HTML, or when called by some script.

