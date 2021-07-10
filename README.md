# Regex-README

Regular expressions are a way to describe patterns in string data. They are powerful tools for inpecting and processing strings.

## Summary
___

Regex used will be &nbsp;` /^[a-zA-Z0-9_]{5,16}$/ ` &nbsp; for "Username"

## Table of Contents
___

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
___

### Anchors
The characters ^ and $ do not match any of the character of the regex string. They only represent the position before and after, or between characters. They can be used to "anchor" the regex match at a certain position. The ^ matches the position beforre the first character in the string, similarly the $ matches right after the last character in the string. 
### Quantifiers
Indicates the numbers of characters or expressions to match. In thec instance of &nbsp; `{5,16}` &nbsp; will match any alphanumerics in between 5 to 16 characters long.
 
### Grouping Constructs
From the regex used, there is one group being used. 
- `[a-zA-Z0-9_]{5,}` to match at any alphanumerics between 5-16 characters. Will accept lowercase, uppercase, any number between 0-9, and can contain underscore and hyphen.


### Bracket Expressions
Bracket expression indicate a set of characters to match, any invidual character between the brackets will match. For e.g. `[a-zA-Z]` will match any alphabets in lowercase and uppercase.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author
___

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
