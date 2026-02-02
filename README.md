# 3.4 Redacted  

Make a function that takes as input some long string and returns a new string where all proper nouns are replaced with with "[Redacted]"

Assume that any capitalized word is a proper noun. This means the first word of every sentence will be redacted. That's OK.

For an extra challenge you could try:
* Do not redact capitalized words that come at the beginning of a sentence. (don't worry about proper nouns that come at the beginning of a sentence)
* You could replace each name with a string of "*" the same length as the name
* You could replace multiple names in a row with just a single "[Redacted]"
* If you want to get *really* fancy, you can go learn about lists in Python and about the natural language processing library [spacy](https://spacy.io/).