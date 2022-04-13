The config page allows the user to put requirements on all [common popup pages](../Common_Popups/index.md). There are two different types of requirements that can be configured. Both suffix and user-privileges. This setting is universal. Meaning if any change is made it will affect all object popup pages.

## Suffix requirements
The column Suffix requirements allows the user to define which popup pages should be available depending och which suffixes the object has. For instance a user might want do define that the control popup should only be available to objects with the suffix _IO. It is possible to define multiple suffixes by using a comma "," to seperate the different suffixes.

**Example:** _IO,_IS,_M will resultat in that only objects with any of the suffixes will have the control page visible.

## Privileges requirements
The privileges column allows the user to define which user privileges are required to show a certain page. For instance only users with the privilege "control" should be able to show the control page. This is useful to restric which users should be able to access what. It is possible to define multiple privilges using a comma "," to seperate the different privileges.

**Example:** Control,EditUsers. If the user has any of these privilges they will be able to see the control page.





<figure>
    <img src="../pics/Config.png"
         alt="AlarmPopup">
    <figcaption>The config page</figcaption>
</figure>
