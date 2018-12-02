# NCI
Command for checking the JAVA PATH
```sh
sudo update-alternatives --config java

```
## See all the process 
```sh
ps aux | grep java
```
## List all the port open on the system
```sh
netstat -lnptu
```
## check all the HBASE and HDFS proceesses
```sh
jps
```
## Starting Haddop and HBA 
```sh
jps #check the running service if all stoped should display only JPS
```
## Starting HDFS
```sh
/usr/local/hadoop/sbin/start-dfs.sh  
/usr/local/hadoop/sbin/start-yarn.sh
```

## Check Started Services 
```sh
jps
```
## Start HBASE
```sh
/usr/local/hbase/bin/start-hbase.sh 
```
## Check all Services
```sh
jps
```
## Run Hbase shell
```sh
/usr/local/hbase/bin/hbase shell
```
## in HBASE shell run
```sh
status
list
```



