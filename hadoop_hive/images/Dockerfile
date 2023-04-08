FROM registry.cn-hangzhou.aliyuncs.com/bigdata_cloudnative/hadoop:v1

COPY hive-config/* ${HIVE_HOME}/conf/

COPY bootstrap.sh /opt/apache/

COPY mysql-connector-java-5.1.49/mysql-connector-java-5.1.49-bin.jar ${HIVE_HOME}/lib/

RUN sudo mkdir -p /home/hadoop/ && sudo chown -R hadoop:hadoop /home/hadoop/

#RUN yum -y install which
