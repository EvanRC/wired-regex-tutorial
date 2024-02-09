# Wired-Regex-tutorial

Regex, short for regular expression, is a sequence of characters that forms a search pattern. It can be used to check if a string contains the specified search pattern, to replace parts of a string based on the pattern, or to split a string into an array of substrings. It could also be likened to having the key to a cypher. As a cypher key decrypts a coded message, revealing its content. A regex deciphers the 'coded' patterns that are within the text, identifying and extracting data that matches those patterns. It can find and unlock detailed patterns that aren't immedialtely apparent, such as specific sequences of characters, formatting, or data structures. And just as a cypher key is desighned for a specific code, a regex too is crafted for specfic patterns. The precision of a regex allows you to target exactly what it is you are looking for within a text. You could target a particular word, a format like an email address, or a more complex pattern like dates in various formats, and more!

## Summary

In this tutorial, I will be explaining the functionality of a Regex expression to help myself and others knowledge on the subject. In this tutorial we are going to narrow in on the example of Charaacter name validation in an MMORPG. For example, a name validation Regex could ensure that a character name starts with a letter, and can include letters, apostrophies, and spaces, with a total lengh of up to 20 characters. Here is Regex pattern that could do this: 
 `^[A-Za-z][A-Za-z' ]{0,19}$`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Bracket Expressions](#bracket-expressions)

## Regex Components
 Here is an example of a Regex pattern to validate a character name: 
 `^[A-Za-z][A-Za-z' ]{0,19}$`

### Anchors
Anchors are an essential part of a character validation regex because they ensure that the regex does not partially match long strings that include the pattern amidst other characters. Without the start (`^`) and end (`$`) anchors, the regex might validate names that don't actually adhere to the overall validation rules due to them having valid patterns within them. They clearly define the boundaries of our search pattern, making sure that character names start and end exactly as our regex defines. To be more precise (`^`) means that the valid character name must start with the patterns that follow imdedietly after after this symbol. While The (`$`) after the allowed 0-19 characters, the name must come to an end. 
### Quantifiers

### Character Classes

### Bracket Expressions

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
