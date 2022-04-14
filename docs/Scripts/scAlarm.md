## scAlarm
scAlarm is the script responsible for all things alarm. In reality this means two things.

1. Keep the global alarm counter, visible in the navigation bar up-to date with all the active alarms
2. Generate the tree view which presents all object specific alarms in the [alarm popup](../Workviews/Common_Popups/Alarm_Popup.md)

### init
Takes the paramater ref (DataStore in most cases) and counts all active alarms

### ref