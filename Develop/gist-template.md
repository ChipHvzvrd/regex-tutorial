# Email Regex

 /^([a-zA-Z0-9._%-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,3})*$/

Tutorial explaining how the email (common) regex works line by line. 

## Summary

I will be explaining how the email (common) regex works. I will also explain how this regex can be used in applications and what makes it so useful. 

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
- +@ verifies there is a string@anotherstring.
### Anchors
- ^ + $ are present showing the start and end of our expression
### Quantifiers

### OR Operator
- {2,3} this indicates 2 OR 3 word characters (.com,.us,.co, etc.)
### Character Classes
- [a-zA-Z0-9._%-] makes sure the characters used are A-Z lowercase and uppercase, numbers 0-9, and can have periods, underscores, and hyphens.
### Flags

### Grouping and Capturing

### Bracket Expressions

### Escaped Expressions
- \. escapes the previous string and matches with a ".".
### Greedy and Lazy Match
- *? switches our quantifier to lazy and reduces the number of repetitions the expression tries to match the current search parameter.
### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author
My name is Christian Pena and I hope this tutorial was helpful in some way as it helped me to understand regex expressions more. I have a linkedIn page https://www.linkedin.com/in/christian-pena-1434621b5/

and my GitHub link is https://gist.github.com/ChipHvzvrd
