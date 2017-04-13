# SPRING BOOT WEB DEMO WITH JSP

This is a spring boot web demo with jsp and external properties file.
it also has spring boot actuators enabled so gives you health status.
Its a demo app which displays the server name/ server ip / server port
of the server in which is deployed.

### SCREENSHOT
![alt text][screenshot]

[screenshot]:
https://github.com/tuxfight3r/spring-demo/raw/master/app.jpg
"App Screenshot"

```shell

# To Compile the package
mvn clean package

# To run 
mvn spring-boot:run

or 

java -jar target/spring-demo-0.1.0.war

# Health Check URL

curl http://localhost:8080/health

```

