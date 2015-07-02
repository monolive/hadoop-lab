Create and configure KDC across nodes
=====================================

This module will install and configure KDC. Based upon host-principal-keytab-list.csv, it will create principal and copy them in place on each nodes.

You can download the kerberos.csv file from ambari WebUI. 

The file format has changed in between ambari 1.x and ambari 2.x. You will need to specify the ambari version in groups_var/all 

TODO: Use ambari API to get keytab files from REST API



