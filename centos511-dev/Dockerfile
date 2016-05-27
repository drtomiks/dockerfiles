FROM centos:5.11

RUN yum -y update \
 && yum -y install freetype \
 && yum -y install fontconfig \
 && yum -y install gcc gcc-c++ make flex bison gperf ruby \
  openssl-devel freetype-devel fontconfig-devel libicu-devel sqlite-devel \
  libpng-devel libjpeg-devel \
 && yum -y install zlib-devel openssl-devel cpio expat-devel gettext-devel \
 && yum -y install wget \
 && yum -y install curl-devel \
 && cd /usr/local/src \
 && wget http://git-core.googlecode.com/files/git-1.7.9.tar.gz \
 && tar xvzf git-1.7.9.tar.gz \
 && cd git-1.7.9 \
 && ./configure \
 && make \
 && make install