# lab6Feign
To execute this you need to execute the common and Eureka server from lab4 repository to run as well.

If you wish to use Maven, open separate command prompts in the target directory and run these commands:

Start 5 separate copies of the lab-6-word-server

mvn spring-boot:run -Dspring.profiles.active=subject
mvn spring-boot:run -Dspring.profiles.active=verb
mvn spring-boot:run -Dspring.profiles.active=article
mvn spring-boot:run -Dspring.profiles.active=adjective
mvn spring-boot:run -Dspring.profiles.active=noun

http://localhost:8010/ - Eureka running

 http://localhost:8020/sentence. You should see several random sentences appear
