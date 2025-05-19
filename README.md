# Healthcare Management System (Microservices)  

A scalable **Spring Boot**-based microservices architecture for patient management, billing, analytics, and authentication, leveraging modern distributed systems design.  


## 🚀 Key Features  
- **Decoupled Services**: Patient, Billing, Analytics, and Auth services communicate via **gRPC** (synchronous) and **Kafka** (asynchronous events).  
- **Security**: JWT-based authentication with centralized **API Gateway** token validation via **Spring Cloud Gateway**.  
- **Event-Driven Analytics**: Real-time data processing using Kafka (producer/consumer model).  
- **IaC & Cloud Emulation**: Automated AWS-like infrastructure (VPC, ECS, MSK) locally using **LocalStack** and **CloudFormation**.  
- **API Documentation**: OpenAPI/Swagger for all RESTful endpoints.  

## 🛠️ Tech Stack  
- **Backend**: Java 21, Spring Boot 3.x, Spring Cloud Gateway, gRPC  
- **Event Streaming**: Apache Kafka  
- **Database**: PostgreSQL  
- **Infrastructure**: Docker, AWS (LocalStack), CloudFormation (IaC)  
- **Security**: JWT
- **Testing**: Integration Tests (REST-assured) 

## 📦 System Architecture 

![image](https://github.com/user-attachments/assets/efb7d1ee-ddb7-4042-86fc-9638c85ecbdd)

![image](https://github.com/user-attachments/assets/d977c4d8-761d-4503-b957-1ebbc7c83d5b)







