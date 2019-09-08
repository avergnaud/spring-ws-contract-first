
# spring-ws-contract-first

contract first : _helloworld.wsdl_

spring-boot 2.1.8

spring-ws (spring-boot-starter-web-services) / Tomcat 9 / openjdk 8

## build

`org.jvnet.jaxb2.maven2:maven-jaxb2-plugin` ou `org.codehaus.mojo:jaxb2-maven-plugin`

standalone ou cible Tomcat

## run

standalone ou Tomcat 9

client _helloworld-soapui-project.xml_
- standalone : [http://localhost:8080/poc/ws/helloworld.wsdl](http://localhost:8080/poc/ws/helloworld.wsdl)
- Tomcat : [http://localhost:8080/spring-ws-contract-first/poc/ws/helloworld.wsdl](http://localhost:8080/spring-ws-contract-first/poc/ws/helloworld.wsdl)

## misc

[http://tomcat.apache.org/whichversion.html](http://tomcat.apache.org/whichversion.html) : 
apache-tomcat-9.0.24

apache-tomcat-9.0.24>vi bin/catalina.sh : 
`export JRE_HOME=...java-se-8u40-ri/jre`

apache-maven-3.5.4


