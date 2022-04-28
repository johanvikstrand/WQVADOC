scSuffix
===

## `this.readFromFile = function (filePath)`

 * **Parameters:** `filePath` — `String` — relative path from project directory to json file
 * **Returns:** `Object` — JS object representation of read json-file

## `this.writeToFile = function (filePath, object)`

 * **Parameters:**
   * `filePath` — `String` — relative path from project directory to json file
   * `object` — `Object` — js object you want to save as json
 * **Returns:** `Boolean` — True if successful

## `this.alarm = function(tagName, ref)`

Takes a tagName and ref as paramaters and returns true if the tagName has any active alarmTags

 * **Parameters:**
   * `tagName` — `String` — The tagName that we want to search for active alarmTags on
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Boolean` — True if the tagName has any active alarmTags else returns false

## `this.warning = function(tagName, ref)`

 * **Parameters:**
   * `tagName` — `String` — The tagName that we want to search for active warningTags on
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Boolean` — True if the tagName has any active WarningTags else returns false

## `this.getDescription = function(suffix)`

Takes a suffix and returns the description

 * **Parameters:** `suffix` — `String` — The suffix for which we want to find the description for
 * **Returns:** `String` — Description of the suffix as found in Suffix.JSON

## `this.getAlarm = function (tagName, ref)`

Takes a tagName and returns all Alarm tags

 * **Parameters:**
   * `tagName` — `String` — The tagName that we want to search for alarmTags on
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Vector` — A vector with all AlarmTags for this tagName

## `this.getWarning = function (tagName, ref)`

Takes a tagName and returns all Warning tags

 * **Parameters:**
   * `tagName` — `String` — The tagName that we want to search for warningTags on
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Vector` — A vector with all AlarmTags for this tagName

## `this.getAlarmAndWarning = function(tagName, ref)`

Takes a tagName and returns all Alarm and Warning tags

 * **Parameters:**
   * `tagName` — `String` — the tagName that we want to search for warning- and alarmTags on
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Vector` — A vector with all Alarm- and warningTags for this tagName

## `this.getControl = function(tagName, ref)`

Takes a tagName and returns all Control tags

 * **Parameters:**
   * `tagName` — `Stromg` — The tagName that we want to search for controlTags on
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Vector` — A vector with all ControlTags for this tagName

## `this.getControlStatus = function(tagName,ref)`

Takes a tagName and returns all Control Status tags

 * **Parameters:**
   * `tagName` — `String` — The tagName that we want to search for control_statusTags on
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Vector` — A vector with all Control StatusTags for this tagName

## `this.getSuffix = function (tagName, ref)`

Takes a tagName and returns all tags for this tagName

 * **Parameters:**
   * `tagName` — `String` — The tagName that we want to find all the tags for
   * `ref` — `DataStore` — Reference to the DataStore where the tag is defined
 * **Returns:** `Vector` — A vector with all tags for this tagName