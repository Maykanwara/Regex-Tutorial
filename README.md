Welcome to my tutorial. Today we are going to talk about Regex.

Summary
Below is code we will look at to study Regex. The code snippet is a regular expression used to match an email address.

var test = /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
The Components of Regex
//
These forward slashes indicate the start and end of a regular expression.

^
This symbol indicates the beginning of the sting or the line if there is a multiline flag.

(
This symbol indicates groups #1 multiple tokens together and createa a capture group for extracting a substring or using a backreference.

[
This symbol indicates a Character set which is matches any character in the set.

a-z
This alphabet indicates a Range which is matches in the range "a"to "z"(char code 97 to 122). Case sensitive.

0-9
This number indicates a Range which is matches a character in the ranhge "0" to "9" (char code 48 to 57). Case sensitive.

_
This symbol indicates Character which is matches a "_" charater (char code 95).

\.
This symbol indicates Escaped character which is matches a "."character (char code 46).

-
This symbol indicates Character which is matches a "-" character (char code 45).

+
This symbol indicates Quantifier which is matches 1 or more of the preceding token.

@
This symbol indicates Character which is matches a "@" character (char code 64).

(
This symbol indicates Capture group #2 multiple tokens together and createa a capture group for extracting a substring or using a backreference.

[
This symbol indicates a Character set which is matches any character in the set.

\d
This symbol indicates a Digit which is matches any digit character (0-9).

a-z
This alphabet indicates a Range which is matches in the range "a"to "z"(char code 97 to 122). Case sensitive.

\.
This symbol indicates Escaped character which is matches a "."character (char code 46).

-
This symbol indicates Character which is matches a "-" character (char code 45).

+
This symbol indicates Quantifier which is matches 1 or more of the preceding token.

\.
This symbol indicates Escaped character which is matches a "."character (char code 46).

(
This symbol indicates Capture group #3 multiple tokens together and createa a capture group for extracting a substring or using a backreference.

[
This symbol indicates a Character set which is matches any character in the set.

a-z
This alphabet indicates a Range which is matches in the range "a"to "z"(char code 97 to 122). Case sensitive.

\.
This symbol indicates Escaped character which is matches a "."character (char code 46).

{2,6}
This symbol indicates Quantifier which is matches 2 to 6 of the preceding token.

$
This symbol indicates End which is matches the end of the string, or the end of a line if the multiple flag (m) is enabled.

Link to GitHub main project page
[GitHub Gist](gist:599838f96a5aa8fcdd50c5a7679def07)
Github
[GitHub](https://github.com/Maykanwara)
Email
Maykanwara@gmail.com