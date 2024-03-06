FROM  oraclelinux:7.9

COPY infinite.sh /tmp/
RUN yum install openssl-devel -y && \
    yum install libssh2 -y && \
    yum install libssh2-devel -y && \
    yum install mariadb-devel -y && \
    yum install postgresql-devel -y
CMD [ "./tmp/infinite.sh" ]