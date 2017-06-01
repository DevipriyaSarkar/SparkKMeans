# SparkKMeans

A simple Spark application for showing K Means Clustering using sbt and scala.    

**WARNING:** This is a naive implementation of KMeans Clustering and is given as an example! Please use org.apache.spark.ml.clustering.KMeans for more conventional use.

## Pre-requisites
1. Java
2. Python
2. Scala
3. Spark

## How to use?
1. Install Scala plugin for Intellij IDEA.
2. Install SBT plugin for Intellij IDEA.
3. Import this project as a SBT project into your IntelliJ IDEA.
4. Build and run the project.

## How to build JAR?
```
> cd <project-directory>
> sbt compile
> sbt run
> sbt package
```

## How to submit the Spark job to the local master?

```
spark-submit --class SparkKMeans --master local <path-to-the-jar>/<jar-file>.jar
```

Usually the path to the jar file is \<project-directory>/target/scala-\<scala-version>
