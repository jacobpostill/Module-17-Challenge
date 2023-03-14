# The RAG (Regex Amazing Gist) 

Introductory paragraph (replace this with your text)

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
The Anchor is a feature of regex that allows you to determine the positions in strings. They are used so coders do not have to match the character of characters. The main components are the dollar sign ($), word boundary(/b), the caret(^), and lookaround anchors. 

The caret is used to match the begining position. Whereas the dollar sign is used to find the end of a string. The word boundary is used to find positions of words. They do this by matching the position, starting with a word character and ending with a non-word character. Finally, the most advanced anchor is the lookaround anchors. They are able to look behind or after a string to see if there are any patterns (positive) or no patterns (negative).

### Quantifiers
Quantifiers are used to match patterns that do or not occur. This is used for finding specific data within a vast text document anmd validating input. There are four common types of regex asterisk (*), plus sign (+), question mark (?), and curly braces ({}). The asterick see if there are zero or more Matches. The plus sign see if there are one or more Matches. The question mark see if there are zero or one match. Finally, the curly braces are you to see if there is a exactly n times { n }, at least n times { n ,}, or from n to m times { n , m }.


### Grouping Constructs
Grouping constructors are used to help someone groups parts in a regex, allowing someone to apply different rules to a whole group. They can also be used to capture certain parts of the matched text, which is helpful when working with a large text block. There are three main types of Grouping Constructs; Parentheses (), Square brackets [], and The pipe symbol (|). Parentheses are used to group parts of a regex expression together. The square brackets are used to match a certain set of characters, created using the brackets. Finally, the pipe symbol is used to match one, of numerous expressions.

### Bracket Expressions
Bracket Expressions are used to help created character sets and match them. These are useful as they can help create more useful regexs and allow you to find and match more patterns, especially when working with lots of texts.There are three main types of Bracket Expressions; Square brackets [], Range brackets [-], and Negation brackets [^]. The square brackets, as discussed earlier, are used to match a certain set of characters, created using the brackets. The Range brackets [-] are used to match a specific range of characters. Finally, Negation brackets are used to find something that is not in the set.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
