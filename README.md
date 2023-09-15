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

Regex are made up of Components. The most common Components or a Regex are:<br>
  Anchors: 
    Denote the where the pattern begins with a `^` and where the pattern ends with the `$` symbol.

  Character Classes: 
    Define the specific character sets that will be used in the pattern. We see this in the regex I am going over here, an example being `\d` which defines the digits 0-9

  Quantifiers:
    Qua

  Alternation:


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

The "OR" operator in a regex pattern would be `|` and this would define inside the pattern to find a match for either one character set OR a second character set. An example would be `a|b` the pattern would need either `a` OR `b` but not both. The example regex does not use a OR operator

### Flags

Flags are used to modify the behavior of the pattern. The would be added to the end of the pattern an example of a flag would be placing a `i` to make a pattern case insensitive. The regex I am going over here does not have any flags.

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
