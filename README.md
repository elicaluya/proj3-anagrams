# proj3-anagrams
Vocabularly anagrams game for primary school English language learners (ELL)


## Overview

A simple anagram game designed for English-language learning students in 
elementary and middle school.  
Students are presented with a list of vocabulary words (taken from a text file) 
and an anagram.  The anagram is a jumble of some number of vocabulary words, randomly chosen.  Students attempt to type vocabularly words that can be created from the  
jumble.  When a matching word is typed, it is added to a list of solved words. 

The vocabulary word list is fixed for one invocation of the server, so multiple
students connected to the same server will see the same vocabulary list but may 
have different anagrams.

## Authors 

Initial version by M Young;
Revisions by Elijah Caluya

## Assignment

The program uses AJAX interaction to asses the information entered key by key.
The program will check each keystroke the user makes and determines if it matches 
any of the words in the Words column. If any letters the user enters are not in
the jumbled letters, the user is prompted that the letter is not in the selection.


## To run automated tests 
* `nosetests`

There are currently nose tests for vocab.py, letterbag.py, and jumble.py. 



