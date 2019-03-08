# Strings-Making-Anagrams

Alice is taking a cryptography class and finding anagrams to be very useful. We consider two strings to be anagrams of 
each other if the first string's letters can be rearranged to form the second string. In other words, both strings must 
contain the same exact letters in the same exact frequency For example, bacdc and dcbac are anagrams, but bacdc and dcbad are 
not.

Alice decides on an encryption scheme involving two large strings where encryption is dependent on the minimum number of 
character deletions required to make the two strings anagrams. Can you help her find this number?

Given two strings, a and b, that may or may not be of the same length, determine the minimum number of character deletions 
required to make  and  anagrams. Any characters can be deleted from either of the strings.

For example, if a= cde and b=dcf, we can delete  from string  and  from string  so that both remaining strings are and  
which are anagrams.

Function Description

Complete the makeAnagram function in the editor below. It must return an integer representing the minimum total 
characters that must be deleted to make the strings anagrams.

makeAnagram has the following parameter(s):

a: a string
b: a string
Input Format

The first line contains a single string, a. 
The second line contains a single string, b.

Constraints
1. 1<=|a|, |b|<=10*4
2. The strings  and  consist of lowercase English alphabetic letters ascii[a-z].

Output Format
Print a single integer denoting the number of characters you must delete to make the two strings anagrams of each other.
