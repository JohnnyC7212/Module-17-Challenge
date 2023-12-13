# Title (replace with your title)

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
They ensure that the regex matches a string at a specific place. 

Code snippet: 

### Quantifiers
They are symbols or characters that specify the quantity or repetition of the preceding character or group.

Code snippet:
const phoneNumberRegex = /^\d{3}-\d{3}-\d{4}$/;
### Grouping Constructs
They are used to treat part of a pattern as a single unit. 

Code snippet: 
const subexpressionRegex = /(abc)+/;
console.log(subexpressionRegex.test("abcabc"));
console.log*(subexpressionRegex.test("abcabc"));

### Bracket Expressions
Also known as character classes, the are used to define a set of characters that you want to match.

Code snippet:
const singleCharRegex = /[abc]/;
console.log(singleCharRegex.test("a"));
console.log(singleCharRegex.test("d"));

### Character Classes
They are a way to specify a set of characters you're intrested in matching, and they are fundementals to building flexible and powerful regex patterns.

Code snippet:
const specialCharRegex = /[.*+?^${}()|[\]\\]/;
console.log(specialCharRegex.test("*")); // true
console.log(specialCharRegex.test("x")); // false

### The OR Operator
It provides a way to express choice in your regex patterns, allowing you to specify multiple alternatives at a particular position in the string you're trying to match.

Code snippet:
const animalRegex = /(cat|dog)/;

console.log(animalRegex.test("cat")); //true
console.log(animalRegex.test("dog")); //true
console.log(animalRegex.test("bird)); //false

### Flags
It provides flexibilty and control over how the regex engine interprets and matches patterns in the input string.

 Code snippet:
const caseInsensitiveRegex = /example/i;
console.log(caseInsensitiveRegex.test("Example")); //true

### Character Escapes
They are essential for ensuring that specific characters are interupted literally in a regex pattern rather as part of the pattern's syntax.

Code snippet:
const backlashRegex = /\\/; // Matches a literal backslash

## Author

As an individual, I am charaterized by an unwavering pursuit of answers and knowledge. Driven by a passion for understanding, I am committed to exploring diverse topics and delving into the depths of curiosity.

Please be sure to find me on github : https://github.com/JohnnyC7212?tab=repositories
