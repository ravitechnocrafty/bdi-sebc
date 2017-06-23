

Homedirs HDFS
==============

[hdfs@ip-172-31-29-254 root]$ hdfs dfs -ls /user
Found 7 items
drwxr-xr-x   - haley  supergroup          0 2017-06-23 18:52 /user/haley
drwxrwxrwx   - mapred hadoop              0 2017-06-23 18:50 /user/history
drwxrwxr-t   - hive   hive                0 2017-06-23 18:51 /user/hive
drwxrwxr-x   - hue    hue                 0 2017-06-23 18:52 /user/hue
drwxrwxr-x   - oozie  oozie               0 2017-06-23 18:52 /user/oozie
drwxr-xr-x   - saturn supergroup          0 2017-06-23 18:52 /user/saturn
drwxr-x--x   - spark  spark               0 2017-06-23 18:50 /user/spark



CM API call `../api/v14/hosts` 
==============================

URL http://34.229.166.207:7180/api/v14/hosts

{
  "items" : [ {
    "hostId" : "8f07e287-9a9d-45b3-b2a8-3b8426c332ba",
    "ipAddress" : "172.31.17.85",
    "hostname" : "ip-172-31-17-85.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/hostRedirect/8f07e287-9a9d-45b3-b2a8-3b8426c332ba",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 2,
    "totalPhysMemBytes" : 15664570368
  }, {
    "hostId" : "68c455a9-25b9-45d0-bae2-3ed56294c2e7",
    "ipAddress" : "172.31.19.192",
    "hostname" : "ip-172-31-19-192.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/hostRedirect/68c455a9-25b9-45d0-bae2-3ed56294c2e7",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 2,
    "totalPhysMemBytes" : 15664570368
  }, {
    "hostId" : "7c97f5f3-8065-4a79-8c7c-bf2e9c77ad10",
    "ipAddress" : "172.31.26.97",
    "hostname" : "ip-172-31-26-97.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/hostRedirect/7c97f5f3-8065-4a79-8c7c-bf2e9c77ad10",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 2,
    "totalPhysMemBytes" : 15664570368
  }, {
    "hostId" : "aac97da3-ccbc-45dc-93fd-6149e67922f9",
    "ipAddress" : "172.31.29.254",
    "hostname" : "ip-172-31-29-254.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/hostRedirect/aac97da3-ccbc-45dc-93fd-6149e67922f9",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 2,
    "totalPhysMemBytes" : 15664570368
  }, {
    "hostId" : "955dd0ee-7180-4da6-8688-b1430d9796a2",
    "ipAddress" : "172.31.31.121",
    "hostname" : "ip-172-31-31-121.ec2.internal",
    "rackId" : "/default",
    "hostUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/hostRedirect/955dd0ee-7180-4da6-8688-b1430d9796a2",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "commissionState" : "COMMISSIONED",
    "numCores" : 4,
    "numPhysicalCores" : 2,
    "totalPhysMemBytes" : 15664570368
  } ]
}




CM API call `../api/v6/clusters/ravitechnocrafty/services`
======================================================



URL http://34.229.166.207:7180/api/v6/clusters/ravitechnocrafty/services


{
  "items" : [ {
    "name" : "zookeeper",
    "type" : "ZOOKEEPER",
    "clusterRef" : {
      "clusterName" : "cluster"
    },
    "serviceUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/serviceRedirect/zookeeper",
    "serviceState" : "STARTED",
    "healthSummary" : "BAD",
    "healthChecks" : [ {
      "name" : "ZOOKEEPER_CANARY_HEALTH",
      "summary" : "GOOD"
    }, {
      "name" : "ZOOKEEPER_SERVERS_HEALTHY",
      "summary" : "BAD"
    } ],
    "configStalenessStatus" : "FRESH",
    "clientConfigStalenessStatus" : "FRESH",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "displayName" : "ZooKeeper"
  }, {
    "name" : "oozie",
    "type" : "OOZIE",
    "clusterRef" : {
      "clusterName" : "cluster"
    },
    "serviceUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/serviceRedirect/oozie",
    "serviceState" : "STARTED",
    "healthSummary" : "BAD",
    "healthChecks" : [ {
      "name" : "OOZIE_OOZIE_SERVERS_HEALTHY",
      "summary" : "BAD"
    } ],
    "configStalenessStatus" : "FRESH",
    "clientConfigStalenessStatus" : "FRESH",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "displayName" : "Oozie"
  }, {
    "name" : "hue",
    "type" : "HUE",
    "clusterRef" : {
      "clusterName" : "cluster"
    },
    "serviceUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/serviceRedirect/hue",
    "serviceState" : "STARTED",
    "healthSummary" : "BAD",
    "healthChecks" : [ {
      "name" : "HUE_HUE_SERVERS_HEALTHY",
      "summary" : "BAD"
    } ],
    "configStalenessStatus" : "FRESH",
    "clientConfigStalenessStatus" : "FRESH",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "displayName" : "Hue"
  }, {
    "name" : "spark_on_yarn",
    "type" : "SPARK_ON_YARN",
    "clusterRef" : {
      "clusterName" : "cluster"
    },
    "serviceUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/serviceRedirect/spark_on_yarn",
    "serviceState" : "STARTED",
    "healthSummary" : "GOOD",
    "healthChecks" : [ ],
    "configStalenessStatus" : "FRESH",
    "clientConfigStalenessStatus" : "FRESH",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "displayName" : "Spark"
  }, {
    "name" : "hdfs",
    "type" : "HDFS",
    "clusterRef" : {
      "clusterName" : "cluster"
    },
    "serviceUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/serviceRedirect/hdfs",
    "serviceState" : "STARTED",
    "healthSummary" : "BAD",
    "healthChecks" : [ {
      "name" : "HDFS_BLOCKS_WITH_CORRUPT_REPLICAS",
      "summary" : "GOOD"
    }, {
      "name" : "HDFS_CANARY_HEALTH",
      "summary" : "GOOD"
    }, {
      "name" : "HDFS_DATA_NODES_HEALTHY",
      "summary" : "BAD"
    }, {
      "name" : "HDFS_FREE_SPACE_REMAINING",
      "summary" : "GOOD"
    }, {
      "name" : "HDFS_HA_NAMENODE_HEALTH",
      "summary" : "BAD"
    }, {
      "name" : "HDFS_MISSING_BLOCKS",
      "summary" : "GOOD"
    }, {
      "name" : "HDFS_UNDER_REPLICATED_BLOCKS",
      "summary" : "GOOD"
    } ],
    "configStalenessStatus" : "FRESH",
    "clientConfigStalenessStatus" : "FRESH",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "displayName" : "HDFS"
  }, {
    "name" : "yarn",
    "type" : "YARN",
    "clusterRef" : {
      "clusterName" : "cluster"
    },
    "serviceUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/serviceRedirect/yarn",
    "serviceState" : "STARTED",
    "healthSummary" : "BAD",
    "healthChecks" : [ {
      "name" : "YARN_JOBHISTORY_HEALTH",
      "summary" : "BAD"
    }, {
      "name" : "YARN_NODE_MANAGERS_HEALTHY",
      "summary" : "BAD"
    }, {
      "name" : "YARN_RESOURCEMANAGERS_HEALTH",
      "summary" : "BAD"
    }, {
      "name" : "YARN_USAGE_AGGREGATION_HEALTH",
      "summary" : "DISABLED"
    } ],
    "configStalenessStatus" : "FRESH",
    "clientConfigStalenessStatus" : "FRESH",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "displayName" : "YARN (MR2 Included)"
  }, {
    "name" : "hive",
    "type" : "HIVE",
    "clusterRef" : {
      "clusterName" : "cluster"
    },
    "serviceUrl" : "http://ip-172-31-31-121.ec2.internal:7180/cmf/serviceRedirect/hive",
    "serviceState" : "STARTED",
    "healthSummary" : "BAD",
    "healthChecks" : [ {
      "name" : "HIVE_HIVEMETASTORES_HEALTHY",
      "summary" : "BAD"
    }, {
      "name" : "HIVE_HIVESERVER2S_HEALTHY",
      "summary" : "BAD"
    } ],
    "configStalenessStatus" : "FRESH",
    "clientConfigStalenessStatus" : "FRESH",
    "maintenanceMode" : false,
    "maintenanceOwners" : [ ],
    "displayName" : "Hive"
  } ]
}