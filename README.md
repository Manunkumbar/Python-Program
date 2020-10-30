# Python-Program
(a)Write a procedure that takes a string of words separated by spaces (assume no punctuation or capitaliza-tion), together with a "target" word, and shows the position of the target word in the string of words.
 For example, if the string is:

we dont need no education we dont need no thought control no we dont

and the target is the word "dont" then your procedure should return the list 1, 6, 13 because "dont" appears at the 1st, 6th, and 13th position in the string. (We start counting positions of words in the string from 0.) Your procedure should return False if the target word doesn’t appear in the string.


(b)Suppose you are repeatedly looking up targets in a xed long list.
 It might help to build an "inverted index", that shows the positions of all targets, so that this information can be retrieved quickly.
 For example, an inverted index for the above string of words would be:

we: 0, 5, 12

dont: 1, 6, 13

need: 2, 7

no: 3, 8, 11

education: 4 

thought: 9

control: 10

Use an appropriate data structure to represent an inverted index. Write a procedure that, given a string of words, constructs an inverted index, and show how to use the index to look up target words as in part (a).
