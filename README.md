# Answer to 11 questions

### Question 1. (4 points) What is the default block size on HDFS? What is the default replication factor of HDFS on Dataproc?

The default block size on HDFS is 128MB.
Considering the performance and the reliability of storage inDataproc clusters, the default replication factor is set at 2.

### Question 2. (2 points) Use enwiki_test.xml as input and run the program locally on a Single Node cluster using 4 cores. Include your screenshot of the dataproc job. What is the completion time of the task?

The completion time for this job is 9 minutes and 21 seconds. 
<img width="796" alt="Q2" src="https://user-images.githubusercontent.com/90704283/165857641-f0d3b4ba-d287-4022-ae44-4bc45ba92d48.png">
Q3


### Question 3. (2 points) Use enwiki_test.xml as input and run the program under HDFS inside a 3 node cluster (2 worker nodes). Include your screenshot of the dataproc job. Is the performance getting better or worse in terms of completion time? Briefly explain.

The completion time is now 5 minutes and 13 seconds. The performance is improving in terms of completion time when compared with the single node cluster as now we can take advantage of the two worker nodes. 

<img width="796" alt="Q3" src="https://user-images.githubusercontent.com/90704283/165857750-cd8d4fb8-b59f-4404-99fa-84b4f63c85ce.png">


### Question 4. (2 points) For this question, change the default block size in HDFS to be 64MB and repeat Question 3. Include your screenshot of the dataproc job. Record run time, is the performance getting better or worse in terms of completion time? Briefly explain.

The completion time is now 5 minutes and 38 seconds which is only sloightly slower than the time with the default HDSF block size which makes me think that the block size does not have a large impact on running time. 

<img width="796" alt="Q4" src="https://user-images.githubusercontent.com/90704283/165857441-be9bba58-fcba-42de-99eb-81e0fb32507e.png">


