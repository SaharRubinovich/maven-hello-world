FROM anapsix/alpine-java
RUN adduser -D nonroot
USER nonroot
ADD target/my-app-${{steps.bump.outputs.jar_version}}.jar /home/myjar.jar
CMD ["java","-jar","/home/myjar.jar"]