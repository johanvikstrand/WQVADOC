scAlarm
===
## `this.init = function(ref)`

Takes the paramater ref and counts the number of active alarms and sets activeAlarms to this number.

 * **Parameters:** `ref` — `DataStore` —  The DataStore for the system

## `alarmEventHandler = function (tagName, ref, treeView)`

Constructor for the alarmEventHandler

 * **Parameters:**
   * `tagName` — `String` —  Name of the tag for which the alarmEventHandler is created
   * `ref` — `DataStore` —  Reference to the local DataStore of the tag
   * `treeView` — `TreeViewObject` —  Reference to the treeView where the data will be displayed

     <p>

## `this.getAlarms = function ()`

Loops through all alarms in DataStore.Alarms and takes their name and status and pushes them into a returnList

 * **Returns:** `vector` — A vector with all alarms and their status

## `this.build = function ()`

Builds the TreeView model of all alarms