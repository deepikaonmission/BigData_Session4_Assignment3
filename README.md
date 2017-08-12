# BigData_Session4_Assignment3

<<<<<<<-----------  TASK --------------->>>>>>
Write a program to implement wordcount using Pig

NOTE: above task can be completed using grunt shell or using script file. Here, I have used grunt shell. And Pig in mapreduce mode is launched.

<<<<<<<---------- SOLUTION -------------->>>>>>
For above task various screenshots are associated:

Screenshot 1:
It shows how and where wordcount.txt file is created

Screenshot 2:
jobhistoryserver is started

Screenshot 3:
All hadoop daemons are started

Screenshot 4:
It is checked whether wordcount.txt already exists in /user/my_pig_stuff in hdfs or not

Screenshot 5:
Since file does not exist, so file is copied from local fs to hdfs

Screenshot 6.1:
Pig in mapreduce mode is launched

Screenshot 6.2:
Enter in grunt shell

Screenshot 7.1, 7.2 and 7.3:
Loads data in wordFile relation
Describes data in wordFile relation
Displays data in wordFile relation

Screenshot 8.1, 8.2, 8.3:
Tokenize() function is applied on line field of wordFile relation
Describe command is used with tokenizeLines relation
Dump command is used with tokenizeLines relation

Screenshot 9.1, 9.2, 9.3:
Flatten() function is applied on tokenizedLine field of tokenizeLines relation
Describe command is used with flattenTokenizeLines relation
Dump command is used with flattenTokenizeLines relation

Screenshot 10.1, 10.2, 10.3:
Group by operator is applied on words field of flattenTokenizeLines relation
Describe command is used with groupByWords relation
Dump command is used with groupByWords relation

Screenshot 11.1, 11.2, 11.3:
count() function is used on words field of groupByWords relation
Describe command is used with countWords relation
Dump command is used with countWords relation

*******************************************************************************************

