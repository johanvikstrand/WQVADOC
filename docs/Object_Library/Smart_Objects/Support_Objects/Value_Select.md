Value Select
===
This support object is tightly relatived to the [Common Popup: Tabs](../../../Common_Popups/Tab.md). The purpose of this support object is to be able to set what values you want to display in runetime without cluttering the workview. Therefore you can select what suffix you want to display as well as if you want to show suffix description, fetched by [scSuffic.getDescription()] and unit of the tag. Font size of text is set either by **fontSize** or if no value is given it is set by [supportGlobalFontSize]().
### Properties
| Property | Description                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------- |
| stateVar | **This property is set by script and should not be filled out** <br/> Sets path to tag in DataStore |
| fontSize | Sets fontSize of this object                                                                        |