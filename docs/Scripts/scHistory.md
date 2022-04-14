scHistory
===


## `historyHandler = function (History2)`

Constructor - Creates a handler for a History2 object

 * **Parameters:** `-` — `WQObject` — History2 object

## `this.updateGraphs = function (listData)`

Adds/Removes graphs depending on active/inactive.

 * **Parameters:** `listData` — `Array` — - Contains all suffix for given tag in History.kvie

## `this.getLogger = function (tagName)`

Takes a tagName as a parameter and tries to find a logger that is logging this tag. If several loggers are found, returns the logger with shortest sampling interval

 * **Parameters:** `tagName` — `String` — which you want to find the logger for
 * **Returns:** `String` — The name of the logger

## `this.addGraph = function (graph)`

addGraph() - Adds graph, if such graph exists, to History2 object.

 * **Parameters:** `graph` — `Array` — - contains: [Name, tagName, Active(status)] of a graph in list

## `this.removeGraph = function (graph)`

addGraph() - Removes graph, if such graph exists, to History2 object.

 * **Parameters:** `graph` — `Array` — - contains: [Name, tagName, Active(status)] of a graph in list

## `this.generateColors = function (numOfSteps)`

generateColor() - Gives array of evenly seperated over the color spectrum based on number of colors needed

 * **Parameters:** `numOfSteps:` — number steps to get color, means total colors
 * **Returns:** `Array` — returnColors - Array of colors

## `this.load = function (list)`

 * **Parameters:** `list` — `*` — 