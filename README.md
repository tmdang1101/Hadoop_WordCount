# Hadoop_WordCount
A demo using Hadoop to perform a word count task

Run Program Using Command Line:

Provide input file:

hadoop dfs -put "path/wordCountInput" /


Run jar file of the program and produce output to HDFS:

hadoop jar "path/wordCount.jar" /wordCountInput /wordCountOutput
