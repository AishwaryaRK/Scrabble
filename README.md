# Scrabble
*The dictionary(sowpods) is first sorted according to the score of each word.

*Then the dictionary is traversed, and each word is checked with the characters in the rack , if all the characters of the dictionary word are present in the rack , then that word is added in a vector , this vector contains the final list of suggestions for the user.

*To take care of a blank character, we find the characters of the dictionary word in the rack, if the character is not present , we remove the blank space and continue checking the other characters of the dictionary word. 
