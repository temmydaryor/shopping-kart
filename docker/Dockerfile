FROM eclipse-temurin:17-jdk-alpine

WORKDIR /usr/src/app

COPY target/shopping-cart-0.0.1-SNAPSHOT.jar /usr/src/app/app.jar

EXPOSE 8070

ENTRYPOINT ["java", "-jar", "app.jar"]
