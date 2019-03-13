# lab-assignment-1

## Elements tab
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

