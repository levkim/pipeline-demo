FROM tomcat:8-jre8-alpine
RUN rm -rf /usr/local/tomcat/webapps/*
COPY HelloServlets.war /usr/local/tomcat/webapps/HelloServlets.war
CMD ["catalina.sh", "run"]
