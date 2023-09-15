# Email Format Regex

  I will be breaking down a Regular Expression(Regex) from email address format.<br> 
  This is the regex that will be going over here `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Summary

The basic over view of this regex is that it looks for a match of certain characters and a patteren of those characters. Regex is enclosed with with `/` which denotes where the regex is beginning and ending. The anchor `^` defines where the begining of the pattern while `$` defines the end of the pattern.<br>
<br>
The first part of the pattern `([a-z0-9_\.-]+)` matches case sensitive alphanumeric characters and the special characters `_`,`.`, and `-`. It will then look for the addition of the `@` symbol.<br> 
<br>
The next section of the pattern `([\da-z\.-]+)`. This section looks for a digit 0-9 then a lowercase letter a-z. It will also look for the addition of the same special characters as before. It will then look for the next character to be a `.`.<br>
<br>
The final part of the pattern `([a-z\.]{2,6})` will look for a string of lowercase letters and `.` that will be between 2 and 6 characters in length.

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

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
