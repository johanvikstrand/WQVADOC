scTrend
===

## `trendHandler = function(trend)`

Consturctor for a trendObject

 * **Parameters:** `Trend` — `Object` — The trend object to be manipulated

## `this.updateGraphs = function(listData)`

Takes an Array from a list and shows/hides graphs depending on if they are active or not

 * **Parameters:** `listData` — `Array` — The array with all tags and if the should be active or not

## `this.addGraph = function(tagName)`

Takes a tagName and tries to add it at the first available space

 * **Parameters:** `tagName` — `String` — the tagName to be added to the trend

     <p>

## `this.removeGraph = function(tagName)`

Removes the tagName from the trend object

 * **Parameters:** `tagName` — `String` — The tag to be removed from the trend

## `this.getColor = function(index)`

Takes an entry from trend and returns the color

 * **Parameters:** `index` — `Integer` — Index of the color to be returned
 * **Returns:** `Color` — The color belonging to the index

## `this.buildLegend = function(legend)`

Takes a legend object and builds it according to what the trend object is showing

 * **Parameters:** `legend` — `Object` — The legend object to be expanded

## `this.clearLegend = function(legend)`

Takes a legend object and empties it

 * **Parameters:** `legend` — `Oject` — The legend to be cleard