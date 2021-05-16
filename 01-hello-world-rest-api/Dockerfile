FROM openjdk:8-jdk-alpine  	
#Base image needed to run app

EXPOSE 8081

									
ADD target/hello-world-rest-api.jar hello-world-rest-api.jar	
#copy the jar file into the image with same name


ENTRYPOINT ["sh", "-c", "java -jar /hello-world-rest-api.jar"]	
#we need to set the cmd which need to be run at startup	1. inside the sheel 2.run the cmd java -jar in root folder jarfile 
	