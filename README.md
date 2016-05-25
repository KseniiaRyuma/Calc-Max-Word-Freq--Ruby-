# Calc-Max-Word-Freq--Ruby-

The overall goal of the assignment is to write a Ruby class and work with attributes, methods, hashes, and arrays.

The functional goal of the assignment is to read some text from a file and find the word or words that appear the most 
in a line in the file. The way we are instructed to measure “the words that appear the most” is by

1. finding the highest frequency word(s) in each line

2. finding lines in the file whose "highest frequency words" is the greatest value among all lines.


Functional Requirements:

1. Write a class called LineAnalyzer that

• records the location of a line of text in the file

• analyzes a line of text

• figures out the highest frequency word(s) on that line and their frequency count

2. Write a driver class called Solution that

• reads provided ‘test.txt’ file

• creates an array of LineAnalyzers

• selects the ones whose “highest frequency words” are the greatest among all LineAnalyzers

• prints out the results
