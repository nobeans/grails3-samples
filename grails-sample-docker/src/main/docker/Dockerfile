FROM java:8u45-jre

COPY app.war /app.war

EXPOSE 8080

CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.war"]
