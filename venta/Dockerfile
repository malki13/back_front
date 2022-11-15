# FROM openjdk:17-alpine
# ARG JAR_FILE=target/*.jar
# COPY ${JAR_FILE} venta.jar
# ENTRYPOINT ["java","-jar","venta.jar"]

FROM openjdk:17-alpine
COPY venta.jar venta.jar
ENTRYPOINT ["java", "-jar", "venta.jar"]