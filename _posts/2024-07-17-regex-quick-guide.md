---
title: "Regex Quick Guide"
excerpt: "A quick-reference guide to regex syntax, taken from [Lesson 12](https://www.py4e.com/lessons/regex) of the Python for Everybody course"
date: 2024-07-17
last_modified_at: 2024-07-17T23:07:23
header:
  overlay_image: /assets/images/matrix.webp
categories:
  - "Example"
tags:
  - "regex"
  - "Markdown"
---



# Regex Quick Guide

```regex
^        Matches the beginning of the line
$        Matches the end of the line
.        Matches any character
\s       Matches whitespace
\S       Matches any non-whitespace character
*        Repeats a character zero or more times
*?       Repeats a character zero or more times (non-greedy)
+        Repeats a character one or more times
+?       Repeats a character one or more times (non-greedy)
[aeiou]  Matches a single character listed in the set
[^XYZ]   Matches a single character not in the listed set
[a-z0-9] The set of characters can include a range
(        Indicates where string extraction is to start
)        Indicates where string extraction is to end
```


<br />

___

*Remember, if something hasn't gone wrong yet, you're not trying hard enough.*

-Nate
