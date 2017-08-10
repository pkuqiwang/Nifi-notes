# Nifi-notes

## EvaluateJsonPath
Destinate: use flowfile-attribute, this will create new attributes in the flow file
Then add new attribute map to JsonPath like 

## RouteOnAttribute
use evaluateion like the following, here category is an attribute in the incoming flowfile
${category:equals('enterprise')}

## HDFS
Hadoop Configuration Resources: /etc/hadoop/conf/core-site.xml,/etc/hadoop/conf/hdfs-site.xml
Kerberos Principal: ambari-qa@FIELD.HORTONWORKS.COM
Kerberos Keytab: /etc/security/keytabs/smokeuser.headless.keytab

## kafka
Kafka Brokers: qwang-hdp3.field.hortonworks.com:6667 
Security Protocol: SASL_PLAINTEXT
Kerberos Service Name: kafka/qwang-hdp3.field.hortonworks.com@FIELD.HORTONWORKS.COM
Kerberos Principal: ambari-qa@FIELD.HORTONWORKS.COM
Kerberos Keytab: /etc/security/keytabs/smokeuser.headless.keytab
Topic Name: testtopic

## Hive
Database Connection URL: jdbc:hive2://qwang-hdp2.field.hortonworks.com:2181,qwang-hdp0.field.hortonworks.com:2181,qwang-hdp1.field.hortonworks.com:2181/;serviceDiscoveryMode=zooKeeper;zooKeeperNamespace=hiveserver2;principal=hive/_HOST@FIELD.HORTONWORKS.COM

Hive Configuration Resources: /etc/hadoop/conf/core-site.xml,/etc/hive/conf/hive-site.xml
Kerberos Principal: ambari-qa@FIELD.HORTONWORKS.COM
Kerberos Keytab: /etc/security/keytabs/smokeuser.headless.keytab

Use SelectHiveQL:
HiveQL Select Query: select code from default.sample_07 limit 10
