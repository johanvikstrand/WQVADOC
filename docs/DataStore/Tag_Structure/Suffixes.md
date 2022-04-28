Suffixes
===
Adding suffixes to tags is a great tool for categorizing different types of signals with common properties over an asortment of different objects. For example a motor and sensor both output a integer process value. Since the naming and grouping of suffixes can differ between plants and organizations WideQuick VA provides and easy to configure suffix structure. The suffixes and their groupings can be found in the __suffix.json__ file in the WideQuick VA project directory which is then interperted by [scSuffix](/docs/Scripts/scSuffix.md)). 

__suffix.json__ is a JSON file and have the following structure:

``` json
 "suffix_group" : {
    "suffix_name": {
      "Suffix": "_XX",
      "Description": "Suffix description!"
    }
 }
```

- "suffix_group" - A group of suffixes that belong together, for example alarm suffixes
- "suffix_name" - An indetifier of what the suffix handles, for example "isOpen" 
- "Suffix" - The actual suffix ending that you want to use in your tag
- "Description" - A description that will apear in runtime to explain what the suffix does in for example support objects or common popups.

## Create new suffix
 blabls
