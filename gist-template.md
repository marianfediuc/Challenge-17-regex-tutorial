Regex Components
Anchors
Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process.

Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

OR Operator
| Indicates an OR operator. For example: couch|chair finds couch or chair.

Character Classes
a character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string.

Flags
A flag is an optional parameter to a regex that modifies its behavior of searching.

Grouping and Capturing
Groups group multiple patterns as a whole, and capturing groups provide extra submatch information when using a regular expression pattern to match against a string.

Bracket Expressions
Bracket expressions are a list of characters and/or character classes enclosed in brackets

Greedy and Lazy Match
'Greedy' means match longest possible string. 'Lazy' means match shortest possible string.

Boundaries
These 3 positions are word boundaries: Before the first character in a string if the first character is a word character. After the last character in a string if the last character is a word character. Between two characters in a string if one is a word character and the other is not.

Back-references
regular expression commands which refer to a previous part of the matched regular expression

Look-ahead and Look-behind
Lookahead allows to add a condition for “what follows”. Lookbehind is similar, but it looks behind