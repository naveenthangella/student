#rkalluru/d43-ftomcat:TAG
FROM    tomcat:8.5
ADD     student.war webapps/student.war 
ADD     https://s3-us-west-2.amazonaws.com/studentapi-cit/mysql-connector.jar lib/mysql-connector.jar 
COPY    context.xml conf/context.xml 
COPY    catalina.sh bin/catalina.sh 
RUN     chmod +x bin/catalina.sh 