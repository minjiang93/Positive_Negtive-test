# Positive_Negtive-test
Test simple program with Positive and Negative method.
Create Junit test under dos command line.

First, it needs make sure that it's already add jdk to system path.
To check java version in the computer with java -version; javac -version. 
Then, downloading junit-xx.jar and hamcrest-core-1.3.jar.
Assume we put two .jar files and program files in same directory.

To compile java file:
  javac filename.java
To compile junit test java file:
  javac -cp junit-4.13.jar;. testfile.java
To Implement java class:
  java filename
To Implement junit test:
  java -cp junit-4.13.jar;hamcrest-core-1.3.jar;. org.junit.runner.JUnitCore filename
To Implement testrunner:
  java -cp junit-4.13.jar;hamcrest-core-1.3.jar;. filename
