FROM azul/zulu-openjdk-alpine
MAINTAINER Ryan Qiu <ryan_qzf@163.com>
ADD target/notebook-service-1.0.jar notebook.jar
ENTRYPOINT ["java","-jar","/notebook.jar"]
EXPOSE 1111