# redundancy_elimination
C implementation of the Levenshtein, N-gram, Soundex and Jaro-Winkler algorithms to eliminate redundancy 

1. Levenshtein distance 
Informally, the Levenshtein distance between two words is the minimum number of single-character edits (insertions, deletions or substitutions) required to change one word into the other. It is named after the Soviet mathematician Vladimir Levenshtein, who considered this distance in 1965.

![Image of Yaktocat](https://github.com/noubhanidata/redundancy_elimination/blob/3d59ec2beff7f20e28d31057caa68f680b91659b/images/Levenshtein.jpg)

2.N-gram
The main idea behind n-gram similarity is generalizing the concept of the longest common subsequence to encompass n-grams, rather than just unigrams. We formulate n-gram similarity as a function sn, where n is a fixed parameter.

![Image of Yaktocat](https://github.com/noubhanidata/redundancy_elimination/blob/3d59ec2beff7f20e28d31057caa68f680b91659b/images/ngram.gif)

3.Soundex
Soundex is a phonetic algorithm for indexing names by sound, as pronounced in English. The goal is for homophones to be encoded to the same representation so that they can be matched despite minor differences in spelling.Improvements to Soundex are the basis for many modern phonetic algorithms.

![Image of Yaktocat](https://github.com/noubhanidata/redundancy_elimination/blob/3d59ec2beff7f20e28d31057caa68f680b91659b/images/soundnex.png)

4.Jaro-Winkler
The Jaro distance is a measure of edit distance between two strings; its inverse, called the Jaro similarity, is a measure of two strings' similarity: the higher the value, the more similar the strings are. The score is normalized such that 0 equates to no similarities and 1 is an exact match.

![Image of Yaktocat](https://github.com/noubhanidata/redundancy_elimination/blob/3d59ec2beff7f20e28d31057caa68f680b91659b/images/jaro.jpg)
