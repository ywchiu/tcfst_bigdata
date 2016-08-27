# 巨量資料分析系統導入 - Using Hadoop and Spark
=============

### Slides:
https://www.slideshare.net/secret/mMQOWuDUEiPHhH

### [投影片] HBase實作
https://www.slideshare.net/secret/l1bY7L7mKHQkzk

### [操作範例] 如何使用Sqoop彙整結構化資料
https://www.youtube.com/watch?v=ZUdXOwnsPPk

### [操作範例] 如何使用Flume彙整非結構化資料
https://www.youtube.com/watch?v=_XXd35NCS2M

### [操作範例] 如何使用Pig
https://www.youtube.com/watch?v=CRujiTH6w18

https://www.youtube.com/watch?v=EEjJzNwlPpk

### [操作範例] 如何使用Hive
https://www.youtube.com/watch?v=UjxBQSy8IBM

### [實際應用] 使用Hadoop 分析 Facebook 打卡資訊
https://www.youtube.com/watch?v=FQr2nVvkLzc


### Restart HBase
- sudo service zookeeper-server restart
- sudo env JAVA_HOME=/usr/java/jdk1.7.0_67-cloudera /usr/lib/hbase/bin/hbase-daemon.sh restart regionserver
- sudo service hbase-master restart

## Start ipython notebook
- sudo yum install python-pip
- wget http://archive.ipython.org/release/1.2.1/ipython-1.2.1.tar.gz
- tar -zxvf ipython-1.2.1.tar.gz
- cd ipython 
- sudo python setup.py install
- sudo pip install jinja2
- sudo pip install tornado
- sudo pip install pyzmq
- ipython notebook


### Cloudera Pseudo Distributed Mode 安裝說明
- https://www.youtube.com/watch?v=6WTbwb5mTSY
- https://www.youtube.com/watch?v=OXUFHcCxgPk
- https://www.youtube.com/watch?v=C_Pj-g5I60M
- https://www.youtube.com/watch?v=5PW2jx0vmXM

