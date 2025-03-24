## MrKraken's One Page Guide Translations
This repository is dedicated to my one-page guides. I make them in illustrator and from 2025-03-20 am setting them up in a way for people to contribute translations.

The final versions will all be posted alongside my main image with credit to the translators obviously

## How to use
in the \GUIDENAME\ folders there is a variables.xml file
- Branch this repository
- Find `<v:sampleDataset dataSetName="en_GB"></v:sampleDataset>` & copy it
- Paste after `</v:sampleDataset>`, before `</v:sampleDataSets>`
- Change the dataSetName to your region locale (eg fr_FR for french)
- When translation is complete, put in a pull request


## Why No Googlesheet?
I was originally going to set this up as a googlesheet and distribute the link to people who wanted to add translations, but the Adobe variables files are not easily parsed to grab all the variable names. It would have taken me far too long to make a parser for the files so github it is!