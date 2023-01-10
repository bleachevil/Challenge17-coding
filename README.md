# Challenge17-coding (Computer Science for JavaScript: Regex)

## Introductory paragraph
Regular expressions are a sequence of characters that are used for matching character combinations in strings for text matching/searching. In JavaScript, regular expressions are search patterns (JavaScript objects) from sequences of characters. <br />

RegExp makes searching and matching of strings easier and faster. For example, in search engines, logs, editors, etc. there’s a need to filter/match texts easily and efficiently. This is where the RegExp patterns come in, defining search patterns with a sequence of characters.

## Summary

I will provide detail explaination of the components of following regex called "Matching an Email". <br />

Matching an Email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
Literal notation is one method of creating RegExp objects in JavaScript. This method involves the use of RegExp literal syntax. RegExp literal notation involves the enclosing of your expression in slashes (/) without the use of quotation marks. <br />
it also limited the regular experssion and applied slashes (/) at start and end of experssion.

### Anchors
dollar sign ($) and power (^) are consider as anchors.
the power sign applied in the begining of "Matching an Email" which mean the string need to be start based on the condition provided ^([a-z0-9_\.-]+) <br />
the dollar sign applied in the end of "Matching an Email" which mean the string need to be end based on the condition provided (.([a-z\.]{2,6})$/)
({2,6}) this is the quantifiers which will explained below
### Quantifiers
the quantifiers ({2,6}) <br />
this quantifiers has the Curly brackets which mean that the character has been limited. and the number 2 and 6 in the curly brackets is to indicate the minimum 2 characters/Numbers and maximum 6 charaters/Numbers allowed.
in front of the quantifiers is a bracket expression  ([a-z\.]) which will explain below.

### Grouping Constructs
the bracket (()) is to group section and it is usually used before/after anchors which to group the quantifiers and bracket Experssion 

### Bracket Expressions
The square brackets [] denote a character class. A character class will match any of the things inside it.
in the matching the email, [a-z\.] means that it contains a positive integer that between character a to character z (lower case)
[\.] is a character class which will explain below

### Character Classes
the Character Classes is always defined within the bracket expression.
[/.] is indicated that matches any character except the newline character in the mataching the email.

### The OR Operator
the OR Operator (|) is not in the example of the matching the email. <br />
it usually used on the group constuct to indicate either or the condition can be applied.

### Flags
the Flags is not in the example of the matching the email. <br />
it usually applied before end of the expression after the Slash (/) and The two most popular are g, for a global search, and i, for a case-insensitive search.

### Character Escapes
the backslash (\) is used to escape a special character. when you use backslash it escapes the special character to match wit the characters based on the condition.

## Author
Jeff Zhang: [github](https://bleachevil.github.io/)
