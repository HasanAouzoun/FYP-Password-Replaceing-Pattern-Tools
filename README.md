# FYP-Password-Replaceing-Pattern-Tools
The published tools developed for my final year project. The project was to identify the replacement patterns used in RockYou password list.

There are two tools - Filter App and Automated Analysis Script. Both of them are published for Win 64x.

## Filter App
This app filters a list using regular expresion.

To run the app, double click **ConsoleApp.exe**.

There is a **test.txt** file in **Files** directory. This conatins a small example of the RockYou password list.

The project repository can be found [here](https://github.com/HasanAouzoun/FYProject)

## Script
This script takes the final filtered list and a English dictionary list to find the replacement patterns.

The end result would need some manual analysis to conclude the project.

To run the script, it is needed two lists of strings. A password list and the dictionary. Both of them are available in the **Files** folder with test files that have less data.

```
PRP_AutomatedAnalysisScript.exe filtered_list.txt dictionary.txt
```

The project repository can be found [here](https://github.com/HasanAouzoun/PRP_AutomatedAnalysisScript)
