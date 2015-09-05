#Last update:2015.8.30
#2015.9.5 update:tar.gz compressed
#sqlmap-GUI From https://github.com/Hood3dRob1n/SQLMAP-Web-GUI
FROM skye347/test-lamp
MAINTAINER Skye347 "s347419313@gmail.com"
ADD sqlmap-master.tar.gz /var/sqlmap/
ADD sqlmap-webInterface.tar.gz /var/www/html/
CMD /etc/init.d/apache2 start && tail -F /var/log/dockerRun.log && /bin/bash
