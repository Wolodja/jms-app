# Spring Boot JMS Application
Simple Spring Boot JMS application to test sending and receiving JMS messages

To run application

Run docker:

`docker run -it --rm -p 8161:8161 -p 61616:61616 vromero/activemq-artemis`

 Windows users should also configure port of ActiveMQ
 
 Run `docker-machine.exe ip` and copy the IP to the application.properties file as
 `spring.artemis.host`
 
 Next run application and go to ActiveMQ console in browser: 
 
 url: `[ip]:8161` and log in as artemis/simetraehcapa