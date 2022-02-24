# Quotes

## Quotes is an app that allows the user to retrieve a random quote from a JSON quote file. The method getQuotesArray parses the quotes JSON file, and returns an array of Quote objects as per the Quote class constructor. The method getQuote, which takes a Quote array argument and int index argument then returns accesses the Quote array at the index passed in, returning the index's properties of text and author within a concatenated string.

## Collaborators:
- Robb
- Kevin
- Ben
- Robb and I (Kevin) acted as the navigators for Ben, who programmed as the driver. I then forked and cloned down Robb's fork of Ben's repo.

## Instructions:
- After cloning down this repo:
    - Install GSON dependency within build.gradle
    - add idea to gitignore
- To run the app:
    - run the main method in App.java: this should result in a print out of a random quote of the JSON quotes file in the console.
- To test the method: Run the main method within AppTest.java.