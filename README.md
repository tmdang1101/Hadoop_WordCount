# Hadoop_WordCount
A demo using Hadoop to perform a word count task

Run Program Using Command Line:
//provide input file
hadoop dfs -put "path/wordCountInput" /

//run jar file of the program and produce output to HDFS
hadoop jar "path/wordCount.jar" /wordCountInput /wordCountOutput
