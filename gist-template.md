# Regex

Regex or regular expressions are a way to extract information from text.
This works by searching one to many matching and distinct search patterns.
It ranges in passing, replacing/parsing strings, through translating data.
You can use Javascript, Java, VB, C#, C/C++, Python and others.

## Summary

This is a email regex: ^([a-zA-Z0-9._%-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,6})\*$

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

Start Match: \G
Start String: ^ or \A
End String: $ or \Z
Absolute end String: \z
Word Boundary: \b
Non-word boundary: \B

### Quantifiers

Zero or one of a: a?
Zero or more of a: a*
One or more of a: a+
Exactly 3 of a: a{3}
3 or more of a: a{3,}
Between 3 and 6 of a: a{3,6}
Greedy quantifier: a*
Lazy quantifier: a*?
Possessive quantifier: a*+

### Grouping Constructs

Capture Everything: -(...)

### Bracket Expressions

### Character Classes

[a-zA-Z0-9._%-]
[a-zA-Z0-9.-]
[a-zA-Z]
Match unlimited times: +
Match Lowercase: a-z
Match Uppercase: A-Z
Match Numbers: 0-9
Match one character in list: .-
Match one character in list: .\_%-
Assert Position at the end of the String: $
Match the previous token between two and six: {2,6}
Matches the character . with index 46 (2E or 56): \.
Matches a token between zero and unlimited times as possible: \*

### The OR Operator

### Flags

### Character Escapes

## Author

https://github.com/chuseblok
