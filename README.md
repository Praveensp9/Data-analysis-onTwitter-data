Twitter-sentimental-analysis
------------------
------------------

This Program uses ElasticSearch, LingPipe tool kit and MapReduce to classify whether the tweet is positive or negative. 

Pre-requisite for running this program
============================
```
1. Install ElasticSearch and start ElasticSearch with the data downloaded from above
2. Install Hadoop cluster for running MapReduce Job and start the cluster
3. Install Spring Tool Suite because the program is written on Spring Data
4. Install Maven
```
Steps for running the program
============================
1. Download the source
2. Unzip the folder and open a java class Classify.java
3. Edit the path of classifier.txt file (Save and close the file)
4. Go to the download source folder from your terminal window
5. Run maven command " mvn clean compile package"
6. Open Spring Tool Suite and import the project
7. Run the project
