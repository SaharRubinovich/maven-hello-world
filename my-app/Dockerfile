FROM anapsix/alpine-java
RUN useradd -ms /bin/bash newuser
USER non-root
ADD target/my-app-*.jar /home/myjar.jar
CMD ["java","-jar","/home/myjar.jar"]