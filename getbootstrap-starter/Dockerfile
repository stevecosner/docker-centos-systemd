FROM centos/systemd

RUN yum -y install httpd; yum clean all; systemctl enable httpd.service
RUN yum install git -y
RUN git clone https://github.com/stevecosner/getbootstrap-starter.git
RUN cp -r getbootstrap-starter/. /var/www/html
EXPOSE 80

CMD ["/usr/sbin/init"]
