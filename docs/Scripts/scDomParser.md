scDomParser
===

## `DOMParser = function (xmlFilePath)`

Constructor for parsing an XML-file

 * **Parameters:** `String` — xmlFilePath - The file path to the XML file.

## `this.xmlToJs = function (xml)`

builds xml code tagNames, attributes and values into a object tree structure into js

 * **Parameters:** `xml` — `Object` —  document Element of the constructor xml file
 * **Returns:** `Object` —  JSobject representation of XML-file 

     <p>

## `this.parseXML = function (jsonFormatted)`

Parse XML-file into either json or js

 * **Parameters:** `jsonFormatted` — `Boolean` — Sets if the return value will be of the type js or json, true for JSON and false for JS
 * **Returns:** `XML` parsed to JSON string representation or xml parsed to JS