
[saturn@ip-172-31-29-254 ~]$ kinit
Password for saturn@RAVITECHNOCRAFTY.PA:
[saturn@ip-172-31-29-254 ~]$ hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar terasort tgen tsort
17/06/23 19:22:59 INFO terasort.TeraSort: starting
17/06/23 19:23:01 INFO hdfs.DFSClient: Created token for saturn: HDFS_DELEGATION_TOKEN owner=saturn@RAVITECHNOCRAFTY.PA, renewer=yarn, realUser=, issueDate=1498245781682, maxDate=1498850581682, sequenceNumber=1, masterKeyId=2 on 172.31.17.85:8020
17/06/23 19:23:01 INFO security.TokenCache: Got dt for hdfs://ip-172-31-17-85.ec2.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.17.85:8020, Ident: (token for saturn: HDFS_DELEGATION_TOKEN owner=saturn@RAVITECHNOCRAFTY.PA, renewer=yarn, realUser=, issueDate=1498245781682, maxDate=1498850581682, sequenceNumber=1, masterKeyId=2)
17/06/23 19:23:01 INFO input.FileInputFormat: Total input paths to process : 12
Spent 388ms computing base-splits.
Spent 5ms computing TeraScheduler splits.
Computing input splits took 395ms
Sampling 10 splits of 204
Making 8 from 100000 sampled records
Computing parititions took 894ms
Spent 1291ms computing partitions.
17/06/23 19:23:02 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-17-85.ec2.internal/172.31.17.85:8032
17/06/23 19:23:03 INFO mapreduce.JobSubmitter: number of splits:204
17/06/23 19:23:03 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1498245607433_0001
17/06/23 19:23:03 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.17.85:8020, Ident: (token for saturn: HDFS_DELEGATION_TOKEN owner=saturn@RAVITECHNOCRAFTY.PA, renewer=yarn, realUser=, issueDate=1498245781682, maxDate=1498850581682, sequenceNumber=1, masterKeyId=2)
17/06/23 19:23:04 INFO impl.YarnClientImpl: Submitted application application_1498245607433_0001
17/06/23 19:23:04 INFO mapreduce.Job: The url to track the job: http://ip-172-31-17-85.ec2.internal:8088/proxy/application_1498245607433_0001/
17/06/23 19:23:04 INFO mapreduce.Job: Running job: job_1498245607433_0001
17/06/23 19:23:13 INFO mapreduce.Job: Job job_1498245607433_0001 running in uber mode : false
17/06/23 19:23:13 INFO mapreduce.Job:  map 0% reduce 0%
17/06/23 19:23:28 INFO mapreduce.Job:  map 1% reduce 0%
17/06/23 19:23:31 INFO mapreduce.Job:  map 4% reduce 0%
17/06/23 19:23:36 INFO mapreduce.Job:  map 7% reduce 0%
17/06/23 19:23:39 INFO mapreduce.Job:  map 8% reduce 0%
17/06/23 19:23:41 INFO mapreduce.Job:  map 10% reduce 0%
17/06/23 19:23:42 INFO mapreduce.Job:  map 11% reduce 0%
17/06/23 19:23:48 INFO mapreduce.Job:  map 12% reduce 0%
17/06/23 19:23:49 INFO mapreduce.Job:  map 13% reduce 0%
17/06/23 19:23:50 INFO mapreduce.Job:  map 15% reduce 0%
17/06/23 19:23:52 INFO mapreduce.Job:  map 16% reduce 0%
17/06/23 19:23:53 INFO mapreduce.Job:  map 17% reduce 0%
17/06/23 19:23:55 INFO mapreduce.Job:  map 18% reduce 0%
17/06/23 19:23:59 INFO mapreduce.Job:  map 19% reduce 0%
17/06/23 19:24:00 INFO mapreduce.Job:  map 20% reduce 0%
17/06/23 19:24:02 INFO mapreduce.Job:  map 22% reduce 0%
17/06/23 19:24:04 INFO mapreduce.Job:  map 24% reduce 0%
17/06/23 19:24:08 INFO mapreduce.Job:  map 25% reduce 0%
17/06/23 19:24:09 INFO mapreduce.Job:  map 26% reduce 0%
17/06/23 19:24:11 INFO mapreduce.Job:  map 27% reduce 0%
17/06/23 19:24:12 INFO mapreduce.Job:  map 28% reduce 0%
17/06/23 19:24:15 INFO mapreduce.Job:  map 29% reduce 0%
17/06/23 19:24:18 INFO mapreduce.Job:  map 31% reduce 0%
17/06/23 19:24:19 INFO mapreduce.Job:  map 32% reduce 0%
17/06/23 19:24:20 INFO mapreduce.Job:  map 34% reduce 0%
17/06/23 19:24:21 INFO mapreduce.Job:  map 35% reduce 0%
17/06/23 19:24:28 INFO mapreduce.Job:  map 37% reduce 0%
17/06/23 19:24:30 INFO mapreduce.Job:  map 40% reduce 0%
17/06/23 19:24:31 INFO mapreduce.Job:  map 41% reduce 0%
17/06/23 19:24:36 INFO mapreduce.Job:  map 42% reduce 0%
17/06/23 19:24:38 INFO mapreduce.Job:  map 43% reduce 0%
17/06/23 19:24:39 INFO mapreduce.Job:  map 44% reduce 0%
17/06/23 19:24:40 INFO mapreduce.Job:  map 46% reduce 0%
17/06/23 19:24:41 INFO mapreduce.Job:  map 47% reduce 0%
17/06/23 19:24:43 INFO mapreduce.Job:  map 48% reduce 0%
17/06/23 19:24:47 INFO mapreduce.Job:  map 49% reduce 0%
17/06/23 19:24:48 INFO mapreduce.Job:  map 50% reduce 0%
17/06/23 19:24:50 INFO mapreduce.Job:  map 52% reduce 0%
17/06/23 19:24:54 INFO mapreduce.Job:  map 53% reduce 0%
17/06/23 19:24:55 INFO mapreduce.Job:  map 54% reduce 0%
17/06/23 19:24:56 INFO mapreduce.Job:  map 55% reduce 0%
17/06/23 19:24:57 INFO mapreduce.Job:  map 56% reduce 0%
17/06/23 19:24:58 INFO mapreduce.Job:  map 57% reduce 0%
17/06/23 19:25:00 INFO mapreduce.Job:  map 58% reduce 0%
17/06/23 19:25:02 INFO mapreduce.Job:  map 59% reduce 0%
17/06/23 19:25:05 INFO mapreduce.Job:  map 60% reduce 0%
17/06/23 19:25:06 INFO mapreduce.Job:  map 61% reduce 0%
17/06/23 19:25:07 INFO mapreduce.Job:  map 63% reduce 0%
17/06/23 19:25:08 INFO mapreduce.Job:  map 64% reduce 0%
17/06/23 19:25:11 INFO mapreduce.Job:  map 65% reduce 0%
17/06/23 19:25:14 INFO mapreduce.Job:  map 66% reduce 0%
17/06/23 19:25:16 INFO mapreduce.Job:  map 68% reduce 0%
17/06/23 19:25:17 INFO mapreduce.Job:  map 69% reduce 0%
17/06/23 19:25:20 INFO mapreduce.Job:  map 71% reduce 0%
17/06/23 19:25:23 INFO mapreduce.Job:  map 72% reduce 0%
17/06/23 19:25:25 INFO mapreduce.Job:  map 73% reduce 0%
17/06/23 19:25:26 INFO mapreduce.Job:  map 75% reduce 0%
17/06/23 19:25:30 INFO mapreduce.Job:  map 76% reduce 0%
17/06/23 19:25:33 INFO mapreduce.Job:  map 78% reduce 0%
17/06/23 19:25:34 INFO mapreduce.Job:  map 79% reduce 0%
17/06/23 19:25:35 INFO mapreduce.Job:  map 80% reduce 0%
17/06/23 19:25:36 INFO mapreduce.Job:  map 81% reduce 0%
17/06/23 19:25:37 INFO mapreduce.Job:  map 82% reduce 0%
17/06/23 19:25:42 INFO mapreduce.Job:  map 83% reduce 0%
17/06/23 19:25:43 INFO mapreduce.Job:  map 84% reduce 0%
17/06/23 19:25:44 INFO mapreduce.Job:  map 85% reduce 0%
17/06/23 19:25:45 INFO mapreduce.Job:  map 86% reduce 0%
17/06/23 19:25:46 INFO mapreduce.Job:  map 88% reduce 0%
17/06/23 19:25:51 INFO mapreduce.Job:  map 89% reduce 0%
17/06/23 19:25:58 INFO mapreduce.Job:  map 89% reduce 4%
17/06/23 19:25:59 INFO mapreduce.Job:  map 90% reduce 4%
17/06/23 19:26:00 INFO mapreduce.Job:  map 91% reduce 4%
17/06/23 19:26:01 INFO mapreduce.Job:  map 91% reduce 7%
17/06/23 19:26:02 INFO mapreduce.Job:  map 92% reduce 11%
17/06/23 19:26:04 INFO mapreduce.Job:  map 92% reduce 19%
17/06/23 19:26:05 INFO mapreduce.Job:  map 92% reduce 23%
17/06/23 19:26:06 INFO mapreduce.Job:  map 92% reduce 27%
17/06/23 19:26:08 INFO mapreduce.Job:  map 93% reduce 27%
17/06/23 19:26:11 INFO mapreduce.Job:  map 94% reduce 27%
17/06/23 19:26:13 INFO mapreduce.Job:  map 96% reduce 27%
17/06/23 19:26:17 INFO mapreduce.Job:  map 96% reduce 28%
17/06/23 19:26:19 INFO mapreduce.Job:  map 97% reduce 28%
17/06/23 19:26:22 INFO mapreduce.Job:  map 98% reduce 28%
17/06/23 19:26:24 INFO mapreduce.Job:  map 99% reduce 28%
17/06/23 19:26:26 INFO mapreduce.Job:  map 100% reduce 30%
17/06/23 19:26:27 INFO mapreduce.Job:  map 100% reduce 33%
17/06/23 19:26:29 INFO mapreduce.Job:  map 100% reduce 46%
17/06/23 19:26:30 INFO mapreduce.Job:  map 100% reduce 50%
17/06/23 19:26:31 INFO mapreduce.Job:  map 100% reduce 54%
17/06/23 19:26:32 INFO mapreduce.Job:  map 100% reduce 58%
17/06/23 19:26:33 INFO mapreduce.Job:  map 100% reduce 61%
17/06/23 19:26:35 INFO mapreduce.Job:  map 100% reduce 66%
17/06/23 19:26:36 INFO mapreduce.Job:  map 100% reduce 67%
17/06/23 19:26:37 INFO mapreduce.Job:  map 100% reduce 69%
17/06/23 19:26:38 INFO mapreduce.Job:  map 100% reduce 71%
17/06/23 19:26:39 INFO mapreduce.Job:  map 100% reduce 74%
17/06/23 19:26:40 INFO mapreduce.Job:  map 100% reduce 83%
17/06/23 19:26:41 INFO mapreduce.Job:  map 100% reduce 89%
17/06/23 19:26:42 INFO mapreduce.Job:  map 100% reduce 92%
17/06/23 19:26:46 INFO mapreduce.Job:  map 100% reduce 97%
17/06/23 19:26:47 INFO mapreduce.Job:  map 100% reduce 99%
17/06/23 19:26:48 INFO mapreduce.Job:  map 100% reduce 100%
17/06/23 19:26:48 INFO mapreduce.Job: Job job_1498245607433_0001 completed successfully
17/06/23 19:26:48 INFO mapreduce.Job: Counters: 53
	File System Counters
		FILE: Number of bytes read=2931072009
		FILE: Number of bytes written=5825950505
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
		HDFS: Number of bytes read=6553627540
		HDFS: Number of bytes written=6553600000
		HDFS: Number of read operations=636
		HDFS: Number of large read operations=0
		HDFS: Number of write operations=16
	Job Counters
		Launched map tasks=204
		Launched reduce tasks=8
		Data-local map tasks=204
		Total time spent by all maps in occupied slots (ms)=1949704
		Total time spent by all reduces in occupied slots (ms)=423050
		Total time spent by all map tasks (ms)=1949704
		Total time spent by all reduce tasks (ms)=423050
		Total vcore-milliseconds taken by all map tasks=1949704
		Total vcore-milliseconds taken by all reduce tasks=423050
		Total megabyte-milliseconds taken by all map tasks=1996496896
		Total megabyte-milliseconds taken by all reduce tasks=433203200
	Map-Reduce Framework
		Map input records=65536000
		Map output records=65536000
		Map output bytes=6684672000
		Map output materialized bytes=2867393174
		Input split bytes=27540
		Combine input records=0
		Combine output records=0
		Reduce input groups=65536000
		Reduce shuffle bytes=2867393174
		Reduce input records=65536000
		Reduce output records=65536000
		Spilled Records=131072000
		Shuffled Maps =1632
		Failed Shuffles=0
		Merged Map outputs=1632
		GC time elapsed (ms)=29907
		CPU time spent (ms)=1015320
		Physical memory (bytes) snapshot=107548254208
		Virtual memory (bytes) snapshot=333376438272
		Total committed heap usage (bytes)=120663310336
		Peak Map Physical memory (bytes)=520876032
		Peak Map Virtual memory (bytes)=1584939008
		Peak Reduce Physical memory (bytes)=978849792
		Peak Reduce Virtual memory (bytes)=1594183680
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters
		Bytes Read=6553600000
	File Output Format Counters
		Bytes Written=6553600000
17/06/23 19:26:48 INFO terasort.TeraSort: done