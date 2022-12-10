# Regex (Regular Expressions in JS)

Introductory paragraph:

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
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
The ^ anchor signifies that the string begins with the characters following it so that means that
the username must be before the @ sign.

The $ anchor signifies that the string ends with the characters before it so that means that
the (\.[a-zA-Z]{2,5}) must be at the end of the string which stands for the .com .au .edu etc. 
### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

I'm currently a student at Monash University and here is a link to my GitHub!!

GitHub: [github.com/IzzyKhalifa](https://github.com/IzzyKhalifa)