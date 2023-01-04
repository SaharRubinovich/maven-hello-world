FROM anapsix/alpine-java
RUN adduser nonroot
USER nonroot
ADD target/my-app-*.jar /home/myjar.jar
CMD ["java","-jar","/home/myjar.jar"]