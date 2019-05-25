# Maven Based Project

Instance 1: Jenkins Server (AWS)
Build: Jenkins
Port: 8080
Link: ${PUBLIC-IP}:8080/jenkins

Instance 2: Web Server (AWS)
Deploy to Container: Tomcat
Tomcat Port: 8090
Link: ${PUBLIC-IP}:8090/
