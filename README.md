# Alfresco-JavaScript-Console-Examples
A list of javaScript console examples


Perform a simple search:

```javascript
var nodes = search.query({
	query: "cm:name:somethingsomething.docx",
	language: "fts-alfresco"});

nodes.forEach(function(entry) {logger.log(entry.name + ' (' + entry.typeShort + '): ' + entry.nodeRef);});
```
