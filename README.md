# NCI
Command for checking the JAVA PATH
sudo update-alternatives --config java

#See all the process 
ps aux | grep java

#List all the port open on the system
netstat -lnptu

#check all the HBASE and HDFS proceesses
jps

#Starting Haddop and HBA 
jps #check the running service if all stoped should display only JPS

#Starting HDFS
/usr/local/hadoop/sbin/start-dfs.sh  
/usr/local/hadoop/sbin/start-yarn.sh


#Check Started Services 
jps

#Start HBASE
/usr/local/hbase/bin/start-hbase.sh 

#Check all Services
jps

#Run Hbase shell
/usr/local/hbase/bin/hbase shell

#in HBASE shell run
status
list




