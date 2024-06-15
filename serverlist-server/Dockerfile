FROM gcr.io/distroless/java21
ADD target/BedrockConnect-1.0-SNAPSHOT.jar /docker/brc
EXPOSE 19132/udp
CMD ["java", "-Xms256M", "-Xmx256M", "-jar", "/docker/brc/BedrockConnect-1.0-SNAPSHOT.jar", "nodb=true"]
