FROM tencentos/tencentos_server40_mini
MAINTAINER kianli <kianli@tencent.com>
RUN yum -y update \
    && yum -y install nginx \
    && yum clean all
ENTRYPOINT ["nginx", "-g", "daemon off;"]
