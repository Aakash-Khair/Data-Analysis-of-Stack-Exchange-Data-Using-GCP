# Data-Analysis-of-Stack-Exchange-Data-Using-GCP

The following was performed on a cluster in Dataproc in Google Cloud Platform (GCP) which already has Hadoop, Pig and Hive.

## Description Of Tasks Performed

### 1.Acquire the top 200,000 posts by view count from stackexchange

### 2.Using pig or MapReduce, extract, transform and load the data as applicable

### 3.Using hive and/or MapReduce, get:
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i).	The top 10 posts by a score
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii).	The top 10 users by post score
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iii).	The number of distinct users, who used the word ‘Hadoop’ in one of their posts

### 4.Using MapReduce calculate the per-user TF-IDF (just submit the top 10 terms for each of the top 10 users from Query 3.ii) <br/>


### Formula To Calculate TF-IDF
TFIDF = n/N * log(D/m) n is the number of times a word is in a document N is the sum of all n's of a document


### References: 

1.https://pig.apache.org/docs/r0.17.0/api/org/apache/pig/piggybank/storage/CSVExcelStorage.html 
2.https://www.geeksforgeeks.org/tf-idf-model-for-page-ranking/ 
3.https://data.stackexchange.com/stackoverflow/query/new

