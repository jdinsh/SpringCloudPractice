#Spring cloud practice

##Spring cloud components

### Configuration
* Move the configuration from the application to a centralized store across all the environments
* Spring cloud config server
* Config client retreive the configuration from the server on the startup
    * Can be notified of changes and process changes in a refresh events.
  
* Service Discovery
    * With the dynamic nature of any cloud native applicvation, depending on things like URLS can be problematic.
    * Service Discovery allows microservices to easily discover the routes to services it needs to user.
    * Netflix Eureka, Zooper, Consul
* Circuit Breakers
    * 
    
* Routing and Messaging
    * In case of Microservice architecture, so communication between the microservice will be critical.
    * Spring cloud supports communication via http requests or via messaging.
    * Routing and Load Balancing
        * Netflix Ribbon and Open Feign.
    * Async messaging :  RabbitMQ or Kakfa 
        
* API Gateway
    * 
* Tracing
* CI Pipelines and Testing

