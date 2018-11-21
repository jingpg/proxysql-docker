FROM centos:7

# 作者信息
MAINTAINER jingpg "jingpg93@gmail.com"

# 设置时区
ENV TZ Asia/Shanghai
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

COPY src/proxysql.repo /etc/yum.repos.d/proxysql.repo
RUN yum -y install proxysql