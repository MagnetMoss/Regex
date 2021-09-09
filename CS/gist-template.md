# Regex Legendary

Let me introduce you to Regex Legendary. This mardown file will explain the regex components below, let it be known, this will be legendary.

## Summary

Things gone over include, but are not limited to, Anchors, Flags, and Character Escapes. 

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
   Overarching blanket for all the things discussed. Components of Regex include, but are not limited to:
   -  Single Characters:  A single character with no special significance represents that character in the target string.
   - Wild Card: The . (period) special character matches any single character except \n (newline).
   - Bracket Expressions: Represents a character set via a list of characters enclosed by the square brackets: '[' and ']'. It normally matches the target string with any single character from the list.

### Anchors
   Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.

### Quantifiers
   Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

### Grouping Constructs
   Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string.

### Bracket Expressions
   A bracket expression is either a matching list expression or a non-matching list expression.

### Character Classes
   The character class is the most basic regex concept after a literal match. It makes one small sequence of characters match a larger set of characters.

### The OR Operator
   You can use the | operator (logical OR) to match characters or expression of either the left or right of the | operator. For example the (t|T) will match either t or T from the input string.

### Flags
Optional flags are available to specify things like case-insensitive, all matches, and multiline mode.

"regexp = /pattern/gmi; // with flags g,m and i"

### Character Escapes
The backslash character ( \ ) is the escaping character. It can be used to denote an escaped character, a string, literal, or one of the set of supported special characters.

## Author

Jared Rose
Email- 2xF4x0@gmail.com
Github- MagnetMoss
