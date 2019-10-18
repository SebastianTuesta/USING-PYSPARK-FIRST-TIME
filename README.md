# PYSPARK

## DOWNLOAD THIS
* Download pyspark (link: http://spark.apache.org/downloads.html)
* Download hadoop (link: https://archive.apache.org/dist/hadoop/core/hadoop-2.7.0/) (hadoop-2.7.0.tar.gz !!!)

## SET THE PARAMETERS
+ Add the next to enviroment variables of os (in my case, i am using Windows 10):
  - HADOOP_HOME: "C:\hadoop-2.7.0"
  - JAVA_HOME: "C:\Java\jdk1.8.0_171 (It has not to be in Program Files folder!!!)"
  - PYSPARK_PYTHON: "C:\Users\Sebastián\Anaconda3\python.exe"
  - SPARK_HOME: "C:\spark-2.4.3-bin-hadoop2.7\
  - PYSPARK_DRIVER_PYTHON ipython
  - PYSPARK_DRIVER_PYTHON_OPTS notebook
+ Add to the path:
  - C:\spark-2.4.3-bin-hadoop2.7\bin
  - C:\hadoop-2.7.0\bin
  - C:\Java\jdk1.8.0_171\bin 

+ Add to the source C:\hadoop-2.7.0\bin, the next files hadood.dll and winutils.exe that are founded in: https://github.com/steveloughran/winutils/tree/master/hadoop-2.7.1/bin

+ Add the next jar libraries to the next D:\spark-2.4.3-bin-hadoop2.7\jars:
  - https://mvnrepository.com/artifact/org.apache.hadoop/hadoop-aws/2.7.3
  - https://mvnrepository.com/artifact/net.java.dev.jets3t/jets3t/0.9.4

+ If you want to use s3a protocols:
  Add this libraries, to the lib folder of spark, download from maven:
   - aws-java-sdk-1.7.4.jar, verify that the dependencie of your hadoop-aws is compatible with aws-java-sdk.

# POWER BI
Power BI has problems with python´s anaconda. So, the recomendation is install python of this setup: https://github.com/winpython/winpython/releases/tag/2.1.20190928.
Then we must replace the path of Power BI for python.

# CONNECT PYTHON WITH ORACLE 32 BITS
https://oracle.github.io/odpi/doc/installation.html#windows
https://stackoverflow.com/questions/33709391/using-multiple-python-engines-32bit-64bit-and-2-7-3-5
