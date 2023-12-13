# Sample Template Project
Use this as a minimal starting point for your own projects.

## Prerequisite
JDK >= 11 (Only 64-Bit versions supported)  
Maven 3.x
```bash
wget https://dlcdn.apache.org/maven/maven-3/3.8.8/binaries/apache-maven-3.8.8-bin.tar.gz
tar xf apache-maven-3.8.8-bin.tar.gz
export PATH="/path/to/apache-maven-3.8.8/bin:$PATH"
mvn --version
```

## Build and run example

```bash
mvn package
cd target
java -cp deeplearning4j-example-sample-1.0.0-M2-bin.jar org.deeplearning4j.examples.sample.LeNetMNIST
```
