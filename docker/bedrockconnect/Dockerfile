FROM gcr.io/distroless/java21
COPY ./serverlist-server/target/BedrockConnect-1.0-SNAPSHOT.jar /docker/brc
WORKDIR /docker/brc
EXPOSE 19132/udp
CMD ["java", "-Xms256M", "-Xmx256M", "-jar", "BedrockConnect-1.0-SNAPSHOT.jar", "nodb=true"]
