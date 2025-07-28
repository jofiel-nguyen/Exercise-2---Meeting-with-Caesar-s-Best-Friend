# Exercise-2---Meeting-with-Caesar-s-Best-Friend
#Question 3 🤔
```
What is the purpose of the slice() method, and how does it differ from substring()?

Answer 🔑
The slice() method extracts a section of a string and returns it as a new string without modifying the original string. It accepts two parameters: the starting index (inclusive) and the ending index (exclusive).

The slice() and substring() methods are very similar in their basic functionality: both extract a portion of a string. However, they differ in how they handle negative arguments and the order of their arguments:

Negative Arguments:

slice() can accept negative arguments, which count from the end of the string. For example, str.slice(-3) extracts the last three characters.

substring() treats negative arguments as 0. So, str.substring(-3, 5) would be the same as str.substring(0, 5).

Argument Order:

If the first argument to slice() is greater than the second, slice() will return an empty string.

If the first argument to substring() is greater than the second, substring() will swap the arguments internally to ensure the smaller index comes first. For example, str.substring(5, 0) is treated as str.substring(0, 5).
```
