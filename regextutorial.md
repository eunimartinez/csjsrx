# Regex Tutorial 

Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Summary

How matching an email using regex works

regex is defined as a sequence of charecters that defines a search pattern.

regex is used to find patterns within a string, find and replace charecters, and validate input.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

theres two anchors, and they define the specific positions where the text should match 

the anchor charecters are (^) and ($)
(^) start of the string
($) end of string

### Quantifiers

(+)
meaning that there should be atleast 1 character of the regex defined before it 

{2,6}
meaning there could be 2 to 6 characters after the name of the email service 


### Grouping Constructs

are created with () and are used to create seperate groups of regex
ex. username group ([a-z0-9_\.-]+)
    email service group ([\da-z\.-]+)
    domain group ([a-z\.]{2,6})

### Bracket Expressions

are used inside of groups to define the regex



### Character Classes

are used to distingush between charecters and digits 

ex. \d matches any digit 



### Character Escapes

character escapes are used to apply rules to the strings

ex. \n is used for new line, \s is used for whitespace character

## Author

eunice d martinez-gonzalez

https://github.com/eunimartinez