scSuffix
===

## `this.readFromFile = function (filePath)`

 * **Parameters:** `filePath` — `String` — - relative path from project directory to json file
 * **Returns:** `` — object representation of read json-file

## `this.writeToFile = function (filePath, object)`

 * **Parameters:**
   * `filePath` — `String` — - relative path from project directory to json file
   * `object` — `Object` — -  js object you want to save as json
 * **Returns:** `Boolean` — true if successful

## `this.alarm = function(tagName, ref)`

Takes a tagName and ref as paramaters and returns true if the tagName has any active alarmTags

 * **Parameters:**
   * `tagName` — `String` — 
   * `ref` — `DataStore` — 
 * **Returns:** `Boolean` — true if the tagName has any active alarmTags else returns false

## `this.warning = function(tagName, ref)`

 * **Parameters:**
   * `tagName` — `String` — 
   * `ref` — `DataStore` — 
 * **Returns:** `Boolean` — true if the tagName has any active WarningTags else returns false

## `this.getDescription = function(suffix)`

Takes a suffix and returns the description

 * **Parameters:** `suffix` — `String` — 
 * **Returns:** `returnList` — Description of the suffix as found in Suffix.JSON

## `this.getAlarm = function (tagName, ref)`

Takes a tagName and returns all Alarm tags

 * **Parameters:**
   * `tagName` — `String` — 
   * `ref` — `DataStore` — 
 * **Returns:** `` — vector with all AlarmTags for this tagName

## `this.getWarning = function (tagName, ref)`

Takes a tagName and returns all Warning tags

 * **Parameters:**
   * `tagName` — `String` — 
   * `ref` — `DataStore` — 
 * **Returns:** `` — vector with all AlarmTags for this tagName

## `this.getAlarmAndWarning = function(tagName, ref)`

Takes a tagName and returns all Alarm and Warning tags

 * **Parameters:**
   * `tagName` — `String` — 
   * `ref` — `DataStore` — 
 * **Returns:** `` — vector with all Alarm- and warningTags for this tagName

## `this.getControl = function(tagName, ref)`

Takes a tagName and returns all Control tags

 * **Parameters:**
   * `tagName` — `Stromg` — 
   * `ref` — `DataStore` — 
 * **Returns:** `` — vector with all ControlTags for this tagName

## `this.getControlStatus = function(tagName,ref)`

Takes a tagName and returns all Control Status tags

 * **Parameters:**
   * `tagName` — `String` — 
   * `ref` — `DataStore` — 
 * **Returns:** `` — vector with all Control StatusTags for this tagName

## `this.getSuffix = function (tagName, ref)`

Takes a tagName and returns all tags for this tagName

 * **Parameters:**
   * `tagName` — `String` — 
   * `ref` — `DataStore` — 
 * **Returns:** `` — vector with all tags for this tagName
