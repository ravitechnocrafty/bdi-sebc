
> [root@ip-172-31-29-254 ~]# hostname
> ip-172-31-29-254



> [root@ip-172-31-29-254 ~]# mysql --version
> mysql  Ver 14.14 Distrib 5.6.30-76.3, for Linux (x86_64) using  6.0



> [root@ip-172-31-29-254 ~]# mysql -u root -e "SHOW DATABASES;" -p
> Enter password:
> +--------------------+
> | Database           |
> +--------------------+
> | information_schema |
> | hive               |
> | hue                |
> | mysql              |
> | oozie              |
> | performance_schema |
> | rman               |
> | scm                |
> | sentry             |
> | test               |
> +--------------------+