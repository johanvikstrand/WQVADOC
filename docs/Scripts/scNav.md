scNav
===


## `MenuNav = function (rootDir, MenuItemGroup)`

 * **Parameters:** `rootDir` - `Directory` - The root directory where the search begins

     <p>

## `this.getViews = function (currentDir)`

Takes a directory as a paramater and returns a vector with the name and the path for all views in that directory

 * **Parameters:** `currentDir` - `FilePath` - 
 * **Returns:** `returnList` -`Array`  - vector with the name and path for all workviews in the directory

## `this.getDir = function ()`

A function to return all entries in the rootDirectory which was specified in MenuNav

 * **Returns:** `Array` - Returns an array of strings that lists all the entries.

## `this.build = function ()`

Populates the Navbar with all catalogues in the rootdirectory

## `this.collapse = function (subSysList)`

Collapses all catalogues in the NavBar

 * **Parameters:** `subSysList` - `NavBarCatalogueGroup` - 

## `this.expand = function (MenuItem, subSysList)`

Takes a catalogue in the NavBar and expands it.

 * **Parameters:**
   * `MenuItem` - `MenuItem` - the catalogue in the NavBar that is to be expanded
   * `subSysList` - `NavBarCatalogueGroup` - the whole list of catalogues in the navBar
