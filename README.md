
# Big-data-computing-project-1
Word count Project.
In this project, I implemented a data processing algorithim to count the number of distinct words in a document.
Each document consisting of lines of words, I count the number of times each word appears in all the documents.


Main requirements of the project are:
```
Installing IntelliJ IDEA 2020.3.4
Setting up Spark configurations in IntelliJ.
Running the build.gradle file.
```
I implemented the program with different JAVARDD functions such as:

* flatMapToPair()
* mapPartitionsToPair()
* mapToPair()
* groupBy()
* groupByKey()

All borrowed from the [Spark documentation](https://spark.apache.org/docs/latest/submitting-applications.html#master-urls).
