# Healthcare Microservices Project

This is a backend project based on **Spring Boot microservices architecture**.  
I built this project to understand how real-world systems are designed using multiple independent services.

The system is divided into different services like authentication, patient management, billing, etc., and all requests go through an API Gateway.

---

## What this project does

Basically, this project simulates a simple healthcare system where:

- Users can be authenticated
- Patient data can be managed
- Billing operations can be handled
- Services communicate with each other

I tried to follow a structure similar to production-level microservices.

---

## Services in this project

- api-gateway → handles all incoming requests  
- auth-service → authentication & security  
- patient-service → patient data management  
- billing-service → billing related logic  
- analytics-service → basic analytics  
- api-requests → shared request models  
- grpc-requests → used for gRPC communication  
- infrastructure → configs and setup  
- integration-tests → testing  

---

## Tech used

- Java  
- Spring Boot  
- Spring Cloud  
- Spring Security  
- REST APIs  
- gRPC  
- Docker  

---

## How to run

### Run locally

Clone the project:

```bash
git clone https://github.com/your-username/healthcare-microservices.git
cd healthcare-microservices
