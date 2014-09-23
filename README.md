/*
Keypadpblm
==========

My First Program :-) Keypadpblm.

We are daily dealing with mobile phones. But any time, did we think about getting all combination of letters in keypads. A very good start of understanding the problem and how to approach a problem.

Pblm statement:
Print all possible words from phone digits

How to approach a problem:
a. Understand what is the problem (Input, Output format)
   Need to find out all possible string combination for given keys.
   Example:
   Input: 2,3 (Indiates the key in mobile phone) where key 2 is "abc", key 3 is "def"
   Output: ad, ae, af, bd, be, bf, cd, ce, cf
   
b. Analyze Input and Output:
   Analyze Input: We have set of characters for each key. { 0 - "", 1 - "", 2 - "abc", 3 - "def", 4 - "ghi", 5 - "jkl"
                                                            6 - "mno" 7 - "pqrs" 8 - "tuv" 9 - "wxyz" }
   Analyze Output: We should given possible combinations.
   
   Conclusion: Print all possible combination of characters for given number of keys. 
   
c. Find Data Structures could be used

   Input: Input could be an array. We could have double dimensional array with indexes key(0-9) and characters.
          Probably it is a HashTable format.
   Output: String
   
d. Algorithm:
   
   Check the output format: ad, ae, af, bd, be, bf, cd, ce, cf
   Second character (last character) is changed initially till getting all combinations. (ad, ae, af)
   If all combination done, take next possible character for first character.(bd, be, bf)
   
*/
