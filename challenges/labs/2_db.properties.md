
First line
=========

2017-06-23 18:30:37,288 INFO main:com.cloudera.server.cmf.Main: Starting SCM Server. JVM Args: [-Dlog4j.configuration=file:/etc/cloudera-scm-server/log4j.properties, -Dfile.encoding=UTF-8, -Dcmf.root.logger=INFO,LOGFILE, -Dcmf.log.dir=/var/log/cloudera-scm-server, -Dcmf.log.file=cloudera-scm-server.log, -Dcmf.jetty.threshhold=WARN, -Dcmf.schema.dir=/usr/share/cmf/schema, -Djava.awt.headless=true, -Djava.net.preferIPv4Stack=true, -Dpython.home=/usr/share/cmf/python, -XX:+UseConcMarkSweepGC, -XX:+UseParNewGC, -XX:+HeapDumpOnOutOfMemoryError, -Xmx2G, -XX:MaxPermSize=256m, -XX:+HeapDumpOnOutOfMemoryError, -XX:HeapDumpPath=/tmp, -XX:OnOutOfMemoryError=kill -9 %p], Args: [], Version: 5.11.1 (#9 built by jenkins on 20170525-1411 git: 8adcfb8545cb0a35f590717b2626a9ea04948dae)
2017-06-23 18:30:37,375 INFO main:org.mortbay.log: Logging to org.slf4j.impl.Log4jLoggerAdapter(org.mortbay.log) via org.mortbay.log.Slf4jLog

Last line
=========

2017-06-23 18:32:18,446 INFO WebServerImpl:com.cloudera.server.cmf.WebServerImpl: Started Jetty server.

db.properties
==============

# Auto-generated by scm_prepare_database.sh on Fri Jun 23 18:30:15 UTC 2017
#
# For information describing how to configure the Cloudera Manager Server
# to connect to databases, see the "Cloudera Manager Installation Guide."
#
com.cloudera.cmf.db.type=mysql
com.cloudera.cmf.db.host=ip-172-31-29-254.ec2.internal
com.cloudera.cmf.db.name=scm
com.cloudera.cmf.db.user=root
com.cloudera.cmf.db.setupType=EXTERNAL
com.cloudera.cmf.db.password=cdh
