# Regex Tutorial Starter Code

Introductory paragraph (replace this with your text)

## Summary

This guide will provide a basic undertanding of the components of the expresion matching an email 

## Table of Contents

- [Anchors](#anchors)

- [Quantifiers](#quantifiers)

- [OR Operator](#or-operator)

- [Character Classes](#character-classes)

- [Flags](#flags)

- [Grouping and Capturing](#grouping-and-capturing)

- [Bracket Expressions](#bracket-expressions)

- [Greedy and Lazy Match](#greedy-and-lazy-match)

- [Boundaries](#boundaries)

- [Back-references](#back-references)

- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors

The anchor ^ denotes the start of the string  
The anchor $ denotes the end of the string

### Quantifiers

The quantifiers for the expresion matching an email is [2,6]

### OR Operator

In this expresion there no OR operator

### Character Classes

 There are multiple characters classes in regex but the one used in expresion of matching and email is \d
\d- Matches any digit (Arabic numeral) Equivalent to [0-9] For example, /\d/ or /[0-9]/ matches "2" in "B2 is the suite number"

### Flags

Base in my knowledge the expresion of matching an email does not contain flags
Here are few example of flags expresions

i
With this flag the search is case-insensitive: no difference between A and a (see the example below).
g
With this flag the search looks for all matches, without it – only the first match is returned.
m
Multiline mode (covered in the chapter Multiline mode of anchors ^ $, flag "m").
s
Enables “dotall” mode, that allows a dot . to match newline character \n (covered in the chapter Character classes).
u
Enables full Unicode support. The flag enables correct processing of surrogate pairs. More about that in the chapter Unicode: flag "u" and class \p{...}.
y
“Sticky” mode: searching at the exact position in the text (covered in the chapter Sticky flag "y", searching at position)

### Grouping and Capturing

Grouping and Capturing is reprecented by ()

### Bracket Expressions

[a-z0-9_\.-] [\da-z\.-] [a-z\.]

### Greedy and Lazy Match

There no greedy and Lazy Match in the expression matching an email 

### Boundaries

### Back-references

There no Back-references in the expression matching an email 

### Look-ahead and Look-behind

## Author

GitHub Profile (https://github.com/Huertz)
