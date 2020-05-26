# docker-centos-systemd
Create Docker Centos images with systemd.

Example docker run command:

docker run --privileged --name httpd -v /sys/fs/cgroup:/sys/fs/cgroup:ro -p 80:80 -d  httpd
