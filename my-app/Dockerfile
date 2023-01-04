FROM anapsix/alpine-java
USER non-root
ADD target/my-app-*.jar /home/myjar.jar
CMD ["java","-jar","/home/myjar.jar"]