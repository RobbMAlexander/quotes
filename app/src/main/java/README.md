# Lab 08: Quotes
02/23/2022

## Collaborators 
 * [Ben Mills](https://github.com/akkanben), [Kevin LaMarca](https://github.com/KevLaMDev), [Robb Alexander](https://github.com/RobbMAlexander)


## Functionality 

The *quotes* app takes a local JSON file containing 168 quotations and related data (included in repository) and parses the data to strings via the [Gson](https://github.com/google/gson) library.

**Note**: set up Gson dependency as described in the **Requirements** section below for proper functionality.

When run from the command line (with no arguments) in the "quotes" directory, the app prints a random quote and accompanying author.

### Requirements

After initializing the gradle app, in file "build.gradle," add the dependency for GSON (below) within existing `dependencies` block after existing dependencies.

`implementation 'com.google.code.gson:gson:2.9.0'`

