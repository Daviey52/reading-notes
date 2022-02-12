# Class Nineteen

[Home](https://daviey52.github.io/reading-notes/)

## Automation

### Regular Expressions

Regular expression are often shortened as regex and they are sequence of characters that are used to check whether a pattern exist in a given text. They are used at the server side to validate the format of email address or passwords during registration. They are also used for parsing text data files to find , replace or delete certain strings. They aid in the manipulation of textual data that at time is often a perquisite for data science projects involving text mining.

Regular expressions are supported by the re module.

The match () function returns a match object if text matches a given pattern. It otherwise returns None.
Special characters are characters that do not match themselves as seen but have a special meaning when used in regular expressions. They can be though as reserved metacharacters that denote something else and not what they look like.

The search () function scans through a given string/sequence, looking for the location where the regular expression produces a match.

The group () function produces a match by re

^ - caret matches the start of the string while $ matches the end of  a string.
\ Backslash can be used as a recognized escape character and when not treated as so it is treated like any other character passed through the pattern.
\w - Lowercase 'w'. Matches any single letter, digit, or underscore.
\W - Uppercase 'W'. Matches any character not part of \w (lowercase w).
\s - Lowercase 's'. Matches a single whitespace character like: space, newline, tab, return.
\S - Uppercase 'S'. Matches any character not part of \s (lowercase s).
\d - Lowercase d. Matches decimal digit 0-9.
\D - Uppercase d. Matches any character that is not a decimal digit.
\t - Lowercase t. Matches tab.
\n - Lowercase n. Matches newline.
\r - Lowercase r. Matches return.
\A - Uppercase a. Matches only at the start of the string. Works across multiple lines as well.
\Z - Uppercase z. Matches only at the end of the string

### Repetition

 1.+ - Checks if the preceding character appears one or more times starting from that position.

  2.* - Checks if the preceding character appears zero or more times starting from that position.

? - Checks if the preceding character appears exactly zero or one time starting from that position.
{x} - Repeat exactly x number of times.
{x,} - Repeat at least x times or more.
{x, y} - Repeat at least x times but no more than y times.

The group feature of regular expression allows to pick parts of the matching text. Part of the regex bound by () are called group.

When needing to use an expression several time, you can use compile() to save the resulting regular expression.
