scSmartPopup
===

## `smartPopup = function (obj)`

Constructor for smartPopup object - smartPopup handles suffix and privilege requirements and and contains function to build the popup menu

 * **Parameters:** `obj` — `Object` — object clicked in workview that opens popup

## `this.generateTabs = function (suffix)`

generateTabs() - Generates what tabs are available for this particular object

 * **Parameters:** `suffix` — `Object` — Suffixes available in project
 * **Returns:** `Array` — returnList  Tabs available to the smartpopup object

## `this.getTabs = function ()`

Gets the tabs for *This* smartPopup object

 * **Returns:** `Array` — tabs for *this* smartPopup

## `this.updateProperties = function ()`

Updates the properties, suffix and tabs, for *This* smartPopup object and saves to scLibrary array

## `this.getSuffix = function ()`

Gets the available suffixes for *This* smartPopup object to show a tab

 * **Returns:** `Object` —  suffixes available suffixes for *This* smartPopup object

## `this.getObj = function ()`

Gets the object that opened *This* smartPopup object

 * **Returns:** `Object` —  object in workview to open popup

## `this.hasPriv = function (priv)`

Returns a boolean value for if the current user has the input privilege

 * **Parameters:** `priv` — `String` — The privilege that should be tested against the current users privileges
 * **Returns:** `Boolean` — True if the user has the privilege, false otherwise

## `this.build = function (view)`

Populates the workview with appropriate buttons for the popup menu

 * **Parameters:** `view` — `Workview` — View represents the popup window and owns a couple of properties to pass on a reference as we change inbetween different popup views