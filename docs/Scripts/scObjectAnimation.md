scObjectAnimation
===

## `this.rotateBinary= function(boolean,defaultVal,value)`

A function to rotate objects

 * **Parameters:**
   * `boolean` — `boolean` — Decides if the object should rotate or not. True for rotation and false for no rotation
   * `defaultVal` — `Interger` — Starting rotation
   * `value` — `Interger` — How much the object should rotate
 * **Returns:** `Interger` — Outputs the new rotation value

## `this.rotate=function(value,min,max)`

Normalizes min & max and rotates to object between 0-100% (0-90°)

 * **Parameters:**
   * `value` — `Dobule` — The actual value of the max
   * `min` — `Dobule` — The minimum possible value of the tag
   * `max` — `Dobule` — The maximum possible value of the tag
 * **Returns:** `Dobule` — A rotation between 0-90°

## `this.alarmColor=function(tagName,ref)`

Takes a tagName and a refrence DataStore and return a color depending on of the tag has any active Alarms, Warnings or nothing

 * **Parameters:**
   * `tagName` — `String` — The tagName of the object we want to evaluate
   * `ref` — `DataStore` — Reference to the Local DataStore
 * **Returns:** `Color` — Alarm color from current theme
