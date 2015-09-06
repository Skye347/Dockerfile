#Last update:2015.9.5
FROM skye347/lamp
MAINTAINER Skye347 "s347419313@gmail.com"
ADD bWAPP.tar.gz /var/www/html/
ADD apache2/ /etc/apache2/
#WebDAV enabled
CMD a2enmod dav && a2enmod dav_fs && /etc/init.d/mysql start && /etc/init.d/apache2 start && tail -F /var/log/dockerRun.log && /bin/bash
