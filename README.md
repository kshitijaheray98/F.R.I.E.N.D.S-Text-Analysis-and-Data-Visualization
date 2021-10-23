# F.R.I.E.N.D.S-Text-Analysis-and-Data-Visualization

∼The One Where Chandler Has A Python Task~

Task Description -

Task 1: Extracting Dialogue

1. Extract dialogue lines from the original script file.
2. Remove all other meta-data.
3. Return the pre-processed script in a list of tuple(order retained), where the first
item of each tuple is the character name, and the second item of which is the
corresponding cleaned dialogue.
4. Save the returned list to a “.txt” file with “<student id> <clean dialogue>.txt”
naming convention. For example, if your student id is 12345678, then the name
of the output file should be “12345678 clean dialogue.txt”.
 
  
Task 2: Separating Dialogue
   
1. Separate the dialogues of different characters(roles)
2. Output the dialogues of different roles, one line per dialogue, to corresponding
files with “<student id> <character name in lower case>.txt” naming convention2
. For example, if there are 3 characters in total, 3 files will be created,
one for each character respectively.
  
  
Task 3: Obtaining Top 5 Frequent Words For Each Role
  
Line frequency of a word refers to how many lines in a document contains the word.
For example, if a document has 3 lines, the maximum line frequency of a word is 3.34

In this task, you are asked to find top 5 words with highest line frequencies(caseinsensitive) for each role, who has spoken more than 100 unique words and store the information in one DataFrame5 with 3 columns:
  
1. role: to record who the word belongs to(character name in lower case).
2. word: to record the word(in lower case).
3. freq: to record the line frequency of the word.
  
Finally, you need to export the DataFrame created as csv file with naming convention
of “<student id> data.csv” and return the DataFrame created. If your student id is
12345678, then the output file name will be “12345678 data.csv”.
  
  
Task 4: Visualising The Findings From Task 3
  
1. Visualise the DataFrame created in Task 3 with an appropriate graph.
2. Justify the choice of the graph.
3. Provide concise and precise observations.
