# TestJava
For Beginning Java Programming

# Usage
## how to compile
[root@localhost src]# java -d . MainJava/TestMain.java

## how to make jar file
[root@localhost src]# jar -cmvf Manifest.txt Test.jar MainJava/*.class SubJava/*.class

## how to run the jar file
[root@localhost src]# java -jar Test.jar
