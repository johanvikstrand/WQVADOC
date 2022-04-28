scLogger
===

## `this.sortLoggers = function ()`

Reads the loggers XML file and converts all loggers into JavaScript object and places them in a vector for easier access.

## `this.findLogger = function (Name)`

Takes a string, a tagName in most cases and loops through all loggers to see if any of them are logging the tagName. If several are found, returns the logger with shortest logging interval.

 * **Parameters:** `Name` — `String` — The variable to find the logger for
 * **Returns:** The logger that is logging the variable "name". Returns false if no logger is found.