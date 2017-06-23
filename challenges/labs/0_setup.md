
Cloud Provider
=============

AWS

AWS Instances
=============

- 54.210.190.124 ip-172-31-29-254.ec2.internal
- 34.229.166.207 ip-172-31-31-121.ec2.internal
- 54.164.97.255 ip-172-31-17-85.ec2.internal
- 54.147.207.20 ip-172-31-26-97.ec2.internal
- 34.229.204.54 ip-172-31-19-192.ec2.internal


Operative System
================

> [root@ip-172-31-29-254 ~]# uname -a
> Linux ip-172-31-29-254 2.6.32-642.15.1.el6.x86_64 #1 SMP Fri Feb 24 14:31:22 UTC 2017 x86_64 x86_64 x86_64 GNU/Linux

Disk Space
==========


[root@ip-172-31-29-254 ~]# df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvda1      197G  1.6G  186G   1% /
tmpfs           7.3G     0  7.3G   0% /dev/shm



Repo List
=========

[root@ip-172-31-29-254 ~]# yum repolist enabled

Loaded plugins: presto, security
ultra-centos-6.8-base                                                                                            | 3.4 kB     00:00
ultra-centos-6.8-extras                                                                                          | 3.3 kB     00:00
ultra-centos-6.8-updates                                                                                         | 3.4 kB     00:00
ultra-centos-6.x-percona                                                                                         | 2.9 kB     00:00
ultra-centos-6.x-ultrarepo                                                                                       | 2.9 kB     00:00
ultra-centos-6.x-ultrarepo/primary_db                                                                            | 3.5 kB     00:00
repo id                                               repo name                                                                   status
ultra-centos-6.8-base                                 UltraServe CentOS-6.8 - Base                                                5,089
ultra-centos-6.8-extras                               UltraServe CentOS-6.8 - Extras                                                 48
ultra-centos-6.8-updates                              UltraServe CentOS-6.8 - Updates                                               658
ultra-centos-6.x-percona                              UltraServe CentOS-6.x - Percona                                                12
ultra-centos-6.x-ultrarepo                            UltraServe CentOS-6.x - UltraServe Repo Packages                               12
repolist: 5,819


Users and Groups
================

> [root@ip-172-31-29-254 ~]# cat /etc/passwd | grep -i saturn
> saturn:x:2800:2800::/home/saturn:/bin/bash
> [root@ip-172-31-29-254 ~]# cat /etc/passwd | grep -i haley
> haley:x:2900:2900::/home/haley:/bin/bash


> [root@ip-172-31-29-254 ~]# cat /etc/group | grep -i planets
> planets:x:2902:saturn
> [root@ip-172-31-29-254 ~]# cat /etc/group | grep -i comets
> comets:x:2901:haley
