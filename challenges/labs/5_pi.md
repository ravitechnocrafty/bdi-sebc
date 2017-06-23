
[haley@ip-172-31-29-254 ~]$ hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar pi 1 1000
Number of Maps  = 1
Samples per Map = 1000
Wrote input for Map #0
Starting Job
17/06/23 19:26:39 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-17-85.ec2.internal/172.31.17.85:8032
17/06/23 19:26:39 INFO hdfs.DFSClient: Created token for haley: HDFS_DELEGATION_TOKEN owner=haley@RAVITECHNOCRAFTY.PA, renewer=yarn, realUser=, issueDate=1498245999706, maxDate=1498850799706, sequenceNumber=2, masterKeyId=2 on 172.31.17.85:8020
17/06/23 19:26:39 INFO security.TokenCache: Got dt for hdfs://ip-172-31-17-85.ec2.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.17.85:8020, Ident: (token for haley: HDFS_DELEGATION_TOKEN owner=haley@RAVITECHNOCRAFTY.PA, renewer=yarn, realUser=, issueDate=1498245999706, maxDate=1498850799706, sequenceNumber=2, masterKeyId=2)
17/06/23 19:26:39 INFO input.FileInputFormat: Total input paths to process : 1
17/06/23 19:26:39 INFO mapreduce.JobSubmitter: number of splits:1
17/06/23 19:26:40 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1498245607433_0002
17/06/23 19:26:40 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.17.85:8020, Ident: (token for haley: HDFS_DELEGATION_TOKEN owner=haley@RAVITECHNOCRAFTY.PA, renewer=yarn, realUser=, issueDate=1498245999706, maxDate=1498850799706, sequenceNumber=2, masterKeyId=2)
17/06/23 19:26:40 INFO impl.YarnClientImpl: Submitted application application_1498245607433_0002
17/06/23 19:26:40 INFO mapreduce.Job: The url to track the job: http://ip-172-31-17-85.ec2.internal:8088/proxy/application_1498245607433_0002/
17/06/23 19:26:40 INFO mapreduce.Job: Running job: job_1498245607433_0002
17/06/23 19:26:48 INFO mapreduce.Job: Job job_1498245607433_0002 running in uber mode : false
17/06/23 19:26:48 INFO mapreduce.Job:  map 0% reduce 0%
17/06/23 19:26:56 INFO mapreduce.Job:  map 100% reduce 0%
17/06/23 19:27:06 INFO mapreduce.Job:  map 100% reduce 100%
17/06/23 19:27:06 INFO mapreduce.Job: Job job_1498245607433_0002 completed successfully
17/06/23 19:27:07 INFO mapreduce.Job: Counters: 53
	File System Counters
		FILE: Number of bytes read=38
		FILE: Number of bytes written=257703
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
		HDFS: Number of bytes read=283
		HDFS: Number of bytes written=215
		HDFS: Number of read operations=7
		HDFS: Number of large read operations=0
		HDFS: Number of write operations=3
	Job Counters
		Launched map tasks=1
		Launched reduce tasks=1
		Data-local map tasks=1
		Total time spent by all maps in occupied slots (ms)=5981
		Total time spent by all reduces in occupied slots (ms)=6606
		Total time spent by all map tasks (ms)=5981
		Total time spent by all reduce tasks (ms)=6606
		Total vcore-milliseconds taken by all map tasks=5981
		Total vcore-milliseconds taken by all reduce tasks=6606
		Total megabyte-milliseconds taken by all map tasks=6124544
		Total megabyte-milliseconds taken by all reduce tasks=6764544
	Map-Reduce Framework
		Map input records=1
		Map output records=2
		Map output bytes=18
		Map output materialized bytes=34
		Input split bytes=165
		Combine input records=0
		Combine output records=0
		Reduce input groups=2
		Reduce shuffle bytes=34
		Reduce input records=2
		Reduce output records=0
		Spilled Records=4
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=54
		CPU time spent (ms)=1590
		Physical memory (bytes) snapshot=658460672
		Virtual memory (bytes) snapshot=3141320704
		Total committed heap usage (bytes)=800587776
		Peak Map Physical memory (bytes)=457924608
		Peak Map Virtual memory (bytes)=1573191680
		Peak Reduce Physical memory (bytes)=200609792
		Peak Reduce Virtual memory (bytes)=1568129024
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters
		Bytes Read=118
	File Output Format Counters
		Bytes Written=97
Job Finished in 27.88 seconds
Estimated value of Pi is 3.14800000000000000000