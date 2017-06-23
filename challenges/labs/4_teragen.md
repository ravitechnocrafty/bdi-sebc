
Tgen execution
===============

[root@ip-172-31-29-254 ~]# su - saturn
[saturn@ip-172-31-29-254 ~]$ cd
[saturn@ip-172-31-29-254 ~]$ time hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar teragen -Ddfs.block.size=33554432  -Dmapred.map.memory.mb=1024 -Dmapred.map.tasks=12 65536000 tgen
17/06/23 19:01:40 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-17-85.ec2.internal/172.31.17.85:8032
17/06/23 19:01:41 INFO terasort.TeraGen: Generating 65536000 using 12
17/06/23 19:01:41 INFO mapreduce.JobSubmitter: number of splits:12
17/06/23 19:01:41 INFO Configuration.deprecation: mapred.map.tasks is deprecated. Instead, use mapreduce.job.maps
17/06/23 19:01:41 INFO Configuration.deprecation: dfs.block.size is deprecated. Instead, use dfs.blocksize
17/06/23 19:01:41 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1498243831728_0002
17/06/23 19:01:41 INFO impl.YarnClientImpl: Submitted application application_1498243831728_0002
17/06/23 19:01:41 INFO mapreduce.Job: The url to track the job: http://ip-172-31-17-85.ec2.internal:8088/proxy/application_1498243831728_0002/
17/06/23 19:01:41 INFO mapreduce.Job: Running job: job_1498243831728_0002
17/06/23 19:01:49 INFO mapreduce.Job: Job job_1498243831728_0002 running in uber mode : false
17/06/23 19:01:49 INFO mapreduce.Job:  map 0% reduce 0%
17/06/23 19:02:08 INFO mapreduce.Job:  map 18% reduce 0%
17/06/23 19:02:10 INFO mapreduce.Job:  map 23% reduce 0%
17/06/23 19:02:11 INFO mapreduce.Job:  map 28% reduce 0%
17/06/23 19:02:13 INFO mapreduce.Job:  map 30% reduce 0%
17/06/23 19:02:14 INFO mapreduce.Job:  map 32% reduce 0%
17/06/23 19:02:15 INFO mapreduce.Job:  map 34% reduce 0%
17/06/23 19:02:16 INFO mapreduce.Job:  map 36% reduce 0%
17/06/23 19:02:17 INFO mapreduce.Job:  map 37% reduce 0%
17/06/23 19:02:18 INFO mapreduce.Job:  map 38% reduce 0%
17/06/23 19:02:20 INFO mapreduce.Job:  map 40% reduce 0%
17/06/23 19:02:21 INFO mapreduce.Job:  map 41% reduce 0%
17/06/23 19:02:22 INFO mapreduce.Job:  map 43% reduce 0%
17/06/23 19:02:24 INFO mapreduce.Job:  map 44% reduce 0%
17/06/23 19:02:27 INFO mapreduce.Job:  map 45% reduce 0%
17/06/23 19:02:30 INFO mapreduce.Job:  map 46% reduce 0%
17/06/23 19:02:32 INFO mapreduce.Job:  map 47% reduce 0%
17/06/23 19:02:35 INFO mapreduce.Job:  map 48% reduce 0%
17/06/23 19:02:39 INFO mapreduce.Job:  map 49% reduce 0%
17/06/23 19:02:41 INFO mapreduce.Job:  map 50% reduce 0%
17/06/23 19:02:45 INFO mapreduce.Job:  map 51% reduce 0%
17/06/23 19:02:48 INFO mapreduce.Job:  map 52% reduce 0%
17/06/23 19:02:53 INFO mapreduce.Job:  map 53% reduce 0%
17/06/23 19:02:56 INFO mapreduce.Job:  map 54% reduce 0%
17/06/23 19:02:59 INFO mapreduce.Job:  map 55% reduce 0%
17/06/23 19:03:02 INFO mapreduce.Job:  map 58% reduce 0%
17/06/23 19:03:03 INFO mapreduce.Job:  map 59% reduce 0%
17/06/23 19:03:05 INFO mapreduce.Job:  map 60% reduce 0%
17/06/23 19:03:09 INFO mapreduce.Job:  map 61% reduce 0%
17/06/23 19:03:17 INFO mapreduce.Job:  map 62% reduce 0%
17/06/23 19:03:23 INFO mapreduce.Job:  map 63% reduce 0%
17/06/23 19:03:27 INFO mapreduce.Job:  map 65% reduce 0%
17/06/23 19:03:28 INFO mapreduce.Job:  map 66% reduce 0%
17/06/23 19:03:29 INFO mapreduce.Job:  map 67% reduce 0%
17/06/23 19:03:32 INFO mapreduce.Job:  map 70% reduce 0%
17/06/23 19:03:34 INFO mapreduce.Job:  map 73% reduce 0%
17/06/23 19:03:35 INFO mapreduce.Job:  map 74% reduce 0%
17/06/23 19:03:36 INFO mapreduce.Job:  map 76% reduce 0%
17/06/23 19:03:37 INFO mapreduce.Job:  map 77% reduce 0%
17/06/23 19:03:38 INFO mapreduce.Job:  map 78% reduce 0%
17/06/23 19:03:40 INFO mapreduce.Job:  map 81% reduce 0%
17/06/23 19:03:41 INFO mapreduce.Job:  map 83% reduce 0%
17/06/23 19:03:42 INFO mapreduce.Job:  map 84% reduce 0%
17/06/23 19:03:43 INFO mapreduce.Job:  map 85% reduce 0%
17/06/23 19:03:44 INFO mapreduce.Job:  map 86% reduce 0%
17/06/23 19:03:45 INFO mapreduce.Job:  map 87% reduce 0%
17/06/23 19:03:46 INFO mapreduce.Job:  map 88% reduce 0%
17/06/23 19:03:47 INFO mapreduce.Job:  map 91% reduce 0%
17/06/23 19:03:48 INFO mapreduce.Job:  map 92% reduce 0%
17/06/23 19:03:49 INFO mapreduce.Job:  map 93% reduce 0%
17/06/23 19:03:51 INFO mapreduce.Job:  map 94% reduce 0%
17/06/23 19:03:52 INFO mapreduce.Job:  map 95% reduce 0%
17/06/23 19:03:53 INFO mapreduce.Job:  map 97% reduce 0%
17/06/23 19:03:55 INFO mapreduce.Job:  map 100% reduce 0%
17/06/23 19:03:55 INFO mapreduce.Job: Job job_1498243831728_0002 completed successfully
17/06/23 19:03:55 INFO mapreduce.Job: Counters: 33
	File System Counters
		FILE: Number of bytes read=0
		FILE: Number of bytes written=1530206
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
		HDFS: Number of bytes read=1025
		HDFS: Number of bytes written=6553600000
		HDFS: Number of read operations=48
		HDFS: Number of large read operations=0
		HDFS: Number of write operations=24
	Job Counters
		Launched map tasks=12
		Other local map tasks=12
		Total time spent by all maps in occupied slots (ms)=1357990
		Total time spent by all reduces in occupied slots (ms)=0
		Total time spent by all map tasks (ms)=1357990
		Total vcore-milliseconds taken by all map tasks=1357990
		Total megabyte-milliseconds taken by all map tasks=1390581760
	Map-Reduce Framework
		Map input records=65536000
		Map output records=65536000
		Input split bytes=1025
		Spilled Records=0
		Failed Shuffles=0
		Merged Map outputs=0
		GC time elapsed (ms)=2117
		CPU time spent (ms)=146930
		Physical memory (bytes) snapshot=4188495872
		Virtual memory (bytes) snapshot=18841440256
		Total committed heap usage (bytes)=4426563584
		Peak Map Physical memory (bytes)=393273344
		Peak Map Virtual memory (bytes)=1579323392
	org.apache.hadoop.examples.terasort.TeraGen$Counters
		CHECKSUM=140750829423462787
	File Input Format Counters
		Bytes Read=0
	File Output Format Counters
		Bytes Written=6553600000

real	2m17.643s
user	0m5.924s
sys	0m0.290s





Output tgen
============

[saturn@ip-172-31-29-254 ~]$ hdfs dfs -ls /user/saturn/tgen
Found 13 items
-rw-r--r--   3 saturn supergroup          0 2017-06-23 19:03 /user/saturn/tgen/_SUCCESS
-rw-r--r--   3 saturn supergroup  546133400 2017-06-23 19:03 /user/saturn/tgen/part-m-00000
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00001
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00002
-rw-r--r--   3 saturn supergroup  546133400 2017-06-23 19:03 /user/saturn/tgen/part-m-00003
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00004
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00005
-rw-r--r--   3 saturn supergroup  546133400 2017-06-23 19:03 /user/saturn/tgen/part-m-00006
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00007
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00008
-rw-r--r--   3 saturn supergroup  546133400 2017-06-23 19:03 /user/saturn/tgen/part-m-00009
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00010
-rw-r--r--   3 saturn supergroup  546133300 2017-06-23 19:03 /user/saturn/tgen/part-m-00011



