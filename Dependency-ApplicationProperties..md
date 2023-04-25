# Dependency to add

Link - https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-actuator/3.0.6

# Application Properties

- Spring boot Actuator: Monitor and manage application in production provides a numbers of endpoints.
		 beans = complete list of spring beans in your app
		 health = application health information
		 metrics = application metrics
		 mappings = details around request mappings
     http://localhost:8080/actuator

- management.endpoints.web.exposure.include=*
- management.endpoints.web.exposure.include=health,metrics

