FROM hub.ark.jd.com/library/centos:7.3
MAINTAINER JohnSmith <xiaosshuaii@gmail.com>
USER root
RUN curl -s http://mirrors.163.com/.help/CentOS7-Base-163.repo >/etc/yum.repos.d/CentOS-Base.repo
RUN yum -y install pcre-devel zlib-devel openssl openssl-devel libcurl
