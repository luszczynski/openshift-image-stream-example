FROM centos:7
# ------------------------
# Instala Ansible e Repos
# ------------------------
RUN yum -y update && yum -y install ansible http://repo.mysql.com/mysql-community-release-el7-5.noarch.rpm https://dl.iuscommunity.org/pub/ius/stable/CentOS/7/x86_64/ius-release-1.0-15.ius.centos7.noarch.rpm && yum clean all
# -------------------------
# Instala pacotes basicos
# -------------------------
RUN yum -y update && yum -y install httpd24u memcached openssl wget curl unzip gcc java-1.8.0-openjdk libxml2 crontabs && yum clean all
# -------------------------
# Adiciona pacotes php
# -------------------------
#RUN yum -y remove php* && yum -y install php56u php56u-common php56u-cli php56u-pear php56u-bcmath php56u-gd php56u-gmp php56u-imap php56u-intl php56u-ldap php56u-mbstring php56u-mysqli php56u-odbc php56u-pdo php56u-pecl-apcu php56u-pspell php56u-zlib php56u-snmp php56u-soap php56u-xml php56u-xmlrpc php56u-zts php56u-devel php56u-pecl-apcu-devel php56u-pecl-memcache php56u-calendar php56u-shmop php56u-intl php56u-mcrypt php56u-pecl-xdebug php56u-mssql freetds freetds-devel php56u-pecl-uploadprogress && yum clean all
# -------------------------
# Adiciona pacotes complementares
# -------------------------
#RUN yum -y install cabextract xorg-x11-font-utils fontconfig https://downloads.sourceforge.net/project/mscorefonts2/rpms/msttcore-fonts-installer-2.6-1.noarch.rpm && yum -y remove gcc && yum clean all
