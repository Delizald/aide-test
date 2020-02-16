# cloud-apache-rhel6
Cloud Apache provisioning and file protection using AIDE pilot project.

This project works the same as the old apache cloud project. The only differences would be nothing siteminder related is installed. httpd.conf and ssl.conf files locked ater creation using 'chattr', the use of AIDE to protect these files and taking the httpd.conf and ssl.conf files after creation from the node.