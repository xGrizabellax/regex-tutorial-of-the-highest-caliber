# Regex-Tutorial-of-the-Highest-Caliber

If you ever needed to search for a particular piece of your code, you would most likely either scroll down until you found it, or maybe use command F to manually search for exactly type in. But what if you need to search for multiple strings that meet certain criteria? What if you don't quite remember what you are searching for, but know a particular pattern it might follow? Regex, or regular expressions, are a series of characters that define a search pattern.

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
An anchor, which is commonly a '^' or '\$' character are used as anchors in regex:
^ - signifies that the characters that follow will begin the string in search.
$ - signifies that the characters that precede it will end the string in search.

### Quantifiers
Quantifiers set the limits of the string that your regex search matches:
\* - matches a pattern 0 or more times,
\+ - matches a pattern 1 or more times,
? - matches a pattern zero or one time,
##### Curly Brackets:
Curly brackets have three possible ways to match a pattern:
{n} - matches 

### Grouping Constructs
Uses (()) to section off portions of a regex search. Each section is known as a subexpression. Unlike bracket expresisons, subexpressions look for an EXACT match. Each subexpression is split up with a colon (:) in between them.
### Bracket Expressions (aka - 'Positive Character Group')
Anything inside of a set of square brackets ([]) that represents a RANGE of characters in search. Commonly uses a hyphen to represent a range. Eg. [1-4] instead of [1234].
If a '^' symbol is added to the beginning of a bracket expression, it will avoid strings that contain the following characters and is known as a 'Negative Character Group'


### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

  For any further assistance, you may contact me at:

  * Github: [xGrizabellax](<https://github.com/xGrizabellax>)

  OR

  * Email: sampagecode@gmail.com
