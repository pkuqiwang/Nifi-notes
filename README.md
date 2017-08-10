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


