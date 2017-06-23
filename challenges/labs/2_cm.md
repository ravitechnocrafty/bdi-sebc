
List repos yum
================
> [root@ip-172-31-31-121 ~]# ls /etc/yum.repos.d
> cloudera-manager.repo  mysql-community.repo  mysql-community-source.repo  ultra-centos-6.8.repo  ultra-centos-6.x.repo




CM Configure DB Command
========================

[root@ip-172-31-31-121 ~]# /usr/share/cmf/schema/scm_prepare_database.sh -h ip-172-31-29-254.ec2.internal mysql scm root cdh
JAVA_HOME=/usr/java/jdk1.7.0_67-cloudera
Verifying that we can write to /etc/cloudera-scm-server
Creating SCM configuration file in /etc/cloudera-scm-server
Executing:  /usr/java/jdk1.7.0_67-cloudera/bin/java -cp /usr/share/java/mysql-connector-java.jar:/usr/share/java/oracle-connector-java.jar:/usr/share/cmf/schema/../lib/* com.cloudera.enterprise.dbutil.DbCommandExecutor /etc/cloudera-scm-server/db.properties com.cloudera.cmf.db.
2017-06-23 18:38:53,053 [main] INFO  com.cloudera.enterprise.dbutil.DbCommandExecutor  - Successfully connected to database.
All done, your SCM database is configured correctly!

