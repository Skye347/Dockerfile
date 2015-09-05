#Last update:2015.8.30
FROM skye347/ubuntu-py
MAINTAINER Skye347 "s347419313@gmail.com"
RUN apt-get install -y apache2
RUN apt-get install -y php5
RUN apt-get install -y mysql-server
EXPOSE 80
CMD /etc/init.d/mysql start && /etc/init.d/apache2 start && tail -F /var/log/dockerRun.log && /bin/bash
