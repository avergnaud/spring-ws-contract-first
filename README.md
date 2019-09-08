
# spring-ws-contract-first

contract first : helloworld.wsdl

spring-boot 2.1.8

spring-ws (spring-boot-starter-web-services) / Tomcat 9 / openjdk 8

## build

org.jvnet.jaxb2.maven2:maven-jaxb2-plugin ou org.codehaus.mojo:jaxb2-maven-plugin

standalone ou cible Tomcat

## run

standalone ou Tomcat 9

client helloworld-soapui-project.xml

## misc

http://tomcat.apache.org/whichversion.html
apache-tomcat-9.0.24

apache-tomcat-9.0.24>vi bin/catalina.sh
	export JRE_HOME=...java-se-8u40-ri/jre

>which mvn
/opt/Apache/apache-maven-3.5.4/bin/mvn

/Tomcat :
http://localhost:8080/spring-ws-contract-first/poc/ws/helloworld.wsdl

standalone :
http://localhost:8080/poc/ws/helloworld.wsdl

