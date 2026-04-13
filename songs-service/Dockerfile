FROM eclipse-temurin:17-jre-alpine
WORKDIR /app

ADD build/libs/*.jar /app/app.jar

CMD ["java", "-jar", "app.jar"]