FROM anapsix/alpine-java
RUN useradd newuser
USER non-root
ADD target/my-app-*.jar /home/myjar.jar
CMD ["java","-jar","/home/myjar.jar"]