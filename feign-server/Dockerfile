# 基于哪个镜像
FROM java:8

# 将本地文件夹挂载到当前容器
VOLUME /tmp

ADD ./target/feign-server-1.0-SNAPSHOT.jar feign-server.jar

# 配置容器启动后执行的命令
ENTRYPOINT ["java","-jar","/feign-server.jar"]