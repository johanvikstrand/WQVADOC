scPrototypes
===

## `String.prototype.replaceAll = function (searchValue, replaceValue)`

Replaces all occurances of searchValue with replaceValue

 * **Parameters:**
   * `searchValue` — `String` — The subString to replace
   * `replaceValue` — `String` — The subString to replace with
 * **Returns:** `String` — The new String with replace value instead of searchValue

## `String.prototype.substringBetween = function (a, b)`

Takes a string and two values and returns the string in between the two values

 * **Parameters:**
   * `a` — `String` — Start string after where the cutting should begin
   * `b` — `String` — End string where the cutting should end
 * **Returns:** `String` — The string between a and b

## `String.prototype.contains = function (searchString)`

Takes a string and searches for a substring

 * **Parameters:** `searchString` — `String` — the substring that should be found
 * **Returns:** `boolean` — Returns true if the substring is found, else if not.

## `String.prototype.split = function (delimiter)`

Takes a string and splits it at every occurance of delimiter

 * **Parameters:** `delimiter` — `String` —  The delimiter where the string should be cut
 * **Returns:** `Array` — Array where entries contain the called upon string split at delimiter

## `String.prototype.includes = function (search, start)`

Determines if substring search is part of the called upon string

 * **Parameters:**
   * `search` — `String` — The string to be found
   * `start` — `Interger` — Index of charchter where the search should begin
 * **Returns:** `Boolean` — True if the substring is found, false if it is not found