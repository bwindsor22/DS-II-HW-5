# DS-II-HW-5

Resources:
* https://regexone.com/
* https://launchschool.com/books/regex/read/introduction
* https://www.youtube.com/watch?v=V8qFhGLjmgo

Write the following methods using RegEx.  The input to each function is a string, and your job is to write a function to determine if the string contains the text described. 

For instance, the first function returns `true` in the case of "My email is abc@gmail.com", and `false` in the case of "My cell phone is 555-555-5555".

1. static bool email(String s) - an email of the form words@gmail.com
2. static bool properName(String s) - matches a proper name like Bob, Smith, Joey
3. static bool number(String s) - a number (integer or decimal, positive or negative) 12, 43.23, -34.5, +98.7, 0, 0.0230
4. static bool ancestor(String s)  - an ancestor like father, mother, great-great-grandmother. Uncles, Aunts, and Cousins are not ancestors.
5. static bool palindrome(String s)  - a 10 letter case insensitive palindrome like "asdfggfdsa". Note: for this problem only assume that the whole string is either a palindrome or not a palindrome. E.g. "a abba" returns false, even though it contains a palindrome.


Please note that unit tests required...How else do you know it works. Unit tests should also include false positive testing.

HW Credit: Dr. Jonathan Roberts
