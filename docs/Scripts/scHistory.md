scHistory
===

## `historyHandler = function (History2)`

Constructor - Creates a handler for a History2 object

 * **Parameters:** `History2` — `WQObject` — An History2 object

## `this.updateGraphs = function (listData)`

Adds/Removes graphs depending on active/inactive.

 * **Parameters:** `listData` — `Array` —  Contains all suffix for given tag in History.kvie

## `this.addGraph = function (graph)`

addGraph() - Adds graph, if such graph exists, to History2 object.

 * **Parameters:** `graph` — `Array` — Containing: [Name, tagName, Active(status)] of a graph in list

## `this.removeGraph = function (graph)`

addGraph() - Removes graph, if such graph exists, to History2 object.

 * **Parameters:** `graph` — `Array` — containing: [Name, tagName, Active(status)] of a graph in list

## `this.generateColors = function (numOfSteps)`

generateColor() - Gives array of evenly seperated over the color spectrum based on number of colors needed

 * **Parameters:** `numOfSteps:` — number steps to get color, means total colors
 * **Returns:** `Array` — returnColors An array of colors

## `this.load = function (list)`

load() - loads/reloads data for the HistoryHandler

 * **Parameters:** `list` — `Array` — list of graphs in the history 2 object connected to the History Handler