# Hadoop_WordCount
Description: A demo using Hadoop to perform a word count task. 
The program consists of a Mapper and a Reducer method to perform MapReduce.
When running the program, we give the input as a text file. The output will be a dictionary of frequencies of each string token in the input.


Run Program Using Command Line:

//Provide input file:

hadoop dfs -put "path/wordCountInput" /


//Run jar file of the program and produce output to HDFS:

hadoop jar "path/wordCount.jar" /wordCountInput /wordCountOutput
