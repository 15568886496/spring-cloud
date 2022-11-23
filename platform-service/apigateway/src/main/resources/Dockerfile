# 基于jdk镜像构建
FROM openjdk:8u102-jre
# 添加应用服务jar到docker服务端
ADD ../../../target/apigateway-1.0-SNAPSHOT.jar app.jar
# 启动命令-定参
ENTRYPOINT ["java", "-jar"]
# 启动命令-变参
CMD ["app.jar"]

