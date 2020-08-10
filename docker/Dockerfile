FROM tomcat
WORKDIR /var/lib/docker/volumes/agent1/1/a/target/
COPY ly-simple-tomcat-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/
RUN cp /usr/local/tomcat/webapps/ly-simple-tomcat-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/ROOT.war
