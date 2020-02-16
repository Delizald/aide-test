This project is meant to be used alongside cloud-apache-rhel6.


Basically what it does is copying the respective node's database located in the ansible server, runs the 'aide' command to check for file integrity. If file check fails then it will overwrite the httpd.conf and ssl.conf file in the node using the backup configuration files created when provisioning the servers using cloud-apache-rhel6 project.

