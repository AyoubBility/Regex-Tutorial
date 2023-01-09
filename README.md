# Regex-Tutorial

This is a Regex tutorial. Regex is a set of characters that together make a pattern.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
/^[A-Za-z][A-Za-z0-9_]{10,30}$/
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The caret "^" and dollar "$" characters are called “anchors”. "^" will be at the beginning of the text while the "$" is at the end. It can be used to test if a string fully matches the pattern. Regex is case-sensitive, so the 'A-Z' indicates upper case, however we can also use lower case because that is also stated as 'a-z'.

### Quantifiers
/^[A-Za-z][A-Za-z0-9_]{10,30}$/

Quantifiers determine how many instances of a character, group, or character class must be present for a match to be found. For example, the {10,30} is a quantifier. These set a limit on the string value, meaning that it is saying that the minimum must be 10 and the maximum must be of 30 characters.

### Grouping and Capturing

Grouping expressions allows us to keep things more organized and easier to exact the characters of a given group. This is used with parentheses "()".

### Bracket Expressions

Anything characters enclosed in '[]' brackets are character classes. Any characters placed inside them will produce a match to the Regex pattern, unless the character(^) precedes the characters in the class. In this case, we have two expressions... '[A-Za-z]' and '[A-Za-z0-9_]'. These expressions can be used to matcha single char or full string.

### Character Classes

These are components within our regular expression that tell us what types of chars to expect. These are any expression within the '[]' brackets.

### The OR Operator

The or operator indicates that it could either of the components that we are separating with the "|". Example, abc|xyz would return abc or xyz.

### Flags

Flags also known as modifiers, modify the output of a regular expression. They can be used in any combination or order. g Global Search will match all instances. i Case insensitive will make matches case-insensitive. m Multiline will anchor meta characters work on each line.

### Character Escapes

The "\" character is used to specify escaped characters both inside and outside a character class.

## Author

Made by Ayoub Bility

GitHub profile: (https://github.com/AyoubBility?tab=repositories)
