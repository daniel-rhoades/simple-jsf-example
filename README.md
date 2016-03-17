# simple-jsf-example
Simple JSF application for testing purposes.

Run it using cargo (running Tomcat) as a quick working demo:

```
mvn clean verify org.codehaus.cargo:cargo-maven2-plugin:run \
    -Dcargo.maven.containerId=tomcat8x \
    -Dcargo.maven.containerUrl=http://www.mirrorservice.org/sites/ftp.apache.org/tomcat/tomcat-8/v8.0.32/bin/apache-tomcat-8.0.32.tar.gz
```
