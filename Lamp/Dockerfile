#Last update:2015.8.30
#2015.9.6 UPDATE:php5-mysql added
FROM skye347/ubuntu-py
MAINTAINER Skye347 "s347419313@gmail.com"
RUN apt-get install -y apache2
RUN apt-get install -y mysql-server
RUN apt-get install -y php5
RUN apt-get install -y php5-mysql
RUN apt-get install -y vim
EXPOSE 80
CMD /etc/init.d/mysql start && /etc/init.d/apache2 start && tail -F /var/log/dockerRun.log && /bin/bash
