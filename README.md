# Regex (Regular Expressions in JS)

## Introduction

A JavaScript RegEx is a sequence of characters that forms a search pattern. You can define what needs to be searched in a text with the help of regular expressions. These expressions can be of any number of characters, be it alphabets, digits or special characters

## Summary

In JavaScript, regular expressions are often used with the two string methods: search() and replace(). 
The search() method uses an expression to search for a match, and returns the position of the match.
The replace() method returns a modified string where the pattern is replaced.
We'll be breaking apart that expression that identifies an email address to the smallest details:
```
/^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-]+)(\.[a-zA-Z]{2,5}){1,2}$/
```

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
The ^ anchor signifies that the string begins with the characters following it so that means that
the username must be before the @ sign.

The $ anchor signifies that the string ends with the characters before it so that means that
the (\.[a-zA-Z]{2,5}) must be at the end of the string which stands for the .com .au .edu etc. 
### Quantifiers
The + quantifier matches the pattern at least one time.
The curly brackets {2,5} used at the end of the expression matches the pattern for 
at least 2 characters to a maximum of 5 [a-zA-Z]
The curly brackets {1,2} used at the end of the expression means that you can use 
[a-zA-Z] that bracket once or maximum twice
### Bracket Expressions
The bracket expressions presents all the characters that can be included in a certain 
pattern so [a-zA-Z] That bracket means that we are looking for any letter lowercase
or uppercase etc you can also include any characters and numbers so it can look 
something like that [a-zA-Z0-9_-.]
### Character Classes
The . character matches all characters except for  (/n) which is the newline character
### Character Escapes
The backslash (\) in a regex escapes a character that otherwise would be interpreted literally. For example, the open curly brace ({) is used to begin a quantifier, but adding a backslash before the open curly brace (\{) means that the regex should look for the open curly brace character instead of beginning to define a quantifier. This is common when looking for strings with special characters that are the same as a particular component of a regex.
## Author

I'm currently a student at Monash University and here is a link to my GitHub!!

GitHub: [github.com/IzzyKhalifa](https://github.com/IzzyKhalifa)