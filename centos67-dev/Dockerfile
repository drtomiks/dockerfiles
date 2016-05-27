FROM centos:6.7

RUN yum -y update \
 && yum -y install freetype \
 && yum -y install fontconfig \
 && yum -y install gcc gcc-c++ make flex bison gperf ruby \
  openssl-devel freetype-devel fontconfig-devel libicu-devel sqlite-devel \
  libpng-devel libjpeg-devel \
 && yum -y install zlib-devel openssl-devel cpio expat-devel gettext-devel \
 && yum -y install wget \
 && yum -y install curl-devel \
 && yum -y install git