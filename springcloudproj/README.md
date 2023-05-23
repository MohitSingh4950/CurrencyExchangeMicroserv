CurrencyExchange Microservices:

The CurrencyExchange Microservices is a Spring 
Boot project that leverages the power of Spring Cloud features for load balancing and fault tolerance. 
The architecture incorporates a Spring Cloud Config Server, allowing users to store port
 and configuration settings in a centralized location. The project utilizes Feign client,
 which replaces RestTemplate for efficient communication between microservices. Additionally,
 an API Gateway, powered by Zuul Server, manages all incoming requests and handles dynamic routing,
 enhancing the overall scalability and flexibility of the system.