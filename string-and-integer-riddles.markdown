## String and Integer Riddles

### Strings

* How can I tell how many characters are in a string? Do spaces count?  .length method, yes spaces count

* How can I capitalize the first character of a string? What
happens if it is a number? .capitalize method, if it is a number, it stays the same

* How can I turn a string backwards?  .reverse method

* How can I tell if two words have the same number of characters? if string1.length == string2.length returns true

* How can I tell if a word has all capital letters?  "string".gsub(/[A-Z]/, '') == "" equals true

* How can I tell if a word has all lower case letters?  "string".gsub(/[A-Z]/, '') == "" equals true

* How can I tell if a word is a palindrome? (The word is the same forwards and
  backwards.) if string1 = string1.reverse returns true

* How can I tell if a sentence is the same forwards and backwards? (ignoring spaces and punctuation) use gsub with regular expression string1.gsub(/\W/,'').reverse ==  string1.gsub(/\W/,'')

* How can I replace an occurrence of a single character in a string with another
character?  .sub method

* How can I replace ALL occurrences of a single character in a string with
another character? .gsub method

* How do I insert 5 asterisks at the start of a string? What about at the end of
a string? What about x asterisks? .prepend method, .insert method

* What if I wanted to have a string that's four characters long, but I want to
make a big string thats 14 characters in length, with the original string in the
middle, with asterisks on either side of the original string to make it reach
the desired length? .center, .ljust, .rjust

* What if I wanted to replace the padding character with spaces? And a variable
total length?  

* What are two ways in which you can determine if an integer is odd? (Or even.)  .odd? .even? methods

* How can I convert a string into a number? .to_i or .to_f

* How can you tell if a number is a palindrome? (303, 1221, 123321)  .to_s.reverse == .to_s

* How can you tell if a number is divisible by 3? By 9? By x? if num % x == 0
