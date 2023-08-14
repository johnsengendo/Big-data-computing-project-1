
# Big-data-computing-project-1
Word count Project.
In this project, I implemented data processing algorithims to count the number of distinct words in a document.
Each document consisted of different words, my program counted the number of times each distinct word appeared in all the documents.


Main requirements of the project are:
```
Installing IntelliJ IDEA 2020.3.4
Setting up Spark configurations in IntelliJ.
Running the build.gradle file.
```
I implemented the program with different JavaRDD processing map-reduce functions such as:

* flatMapToPair()
* mapPartitionsToPair()
* mapToPair()
* groupBy()
* groupByKey()

All borrowed from the [Spark documentation](https://spark.apache.org/docs/latest/submitting-applications.html#master-urls).
