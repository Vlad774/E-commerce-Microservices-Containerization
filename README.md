# E-commerce Microservices Containerization
## Description
This project involves containerizing a microservices-based e-commerce application to enhance scalability, maintainability, and deployment efficiency.

## Technologies
- API Gateway (NGINX): Routes client requests to appropriate backend services.
- Client Service (Angular): Provides a dynamic user interface.
- Product Catalog Service (Node.js) with MongoDB: Manages product listings and search functionalities.
- Order Management Service (Java) with MySQL: Handles order processing and payment transactions.
  
## Workflow
- Information Gathering: Collaborate with developers to understand each microservice's build and deployment processes.
- Dockerfile Creation: Develop Dockerfiles specifying base images, dependencies, and build instructions.
- Docker Compose Configuration: Define a docker-compose.yml file to orchestrate multi-container deployments.
- Building and Testing: Use Docker Compose to build and test services locally.
- Deployment: Push Docker images to a container registry and deploy to the production environment.
     
## Key Features
- Scalability: Independently scale services based on demand.
- Isolation: Operate each microservice in its own container to prevent conflicts.
- Consistency: Maintain uniform environments across development, testing, and production stages.
- Rapid Deployment: Automate builds and deployments for quicker releases.
  

## Walk-through:

 ![First try](https://github.com/Vlad774/E-commerce-Microservices-Containerization/blob/main/Diagramma.png) 
 ![First try](https://github.com/Vlad774/E-commerce-Microservices-Containerization/blob/main/microservices.png) 
 ![First try](https://github.com/Vlad774/E-commerce-Microservices-Containerization/blob/main/vscode_microservices.png)
 ![First try](https://github.com/Vlad774/E-commerce-Microservices-Containerization/blob/main/created.png)
 ![First try](https://github.com/Vlad774/E-commerce-Microservices-Containerization/blob/main/build.png)
 ![First try](https://github.com/Vlad774/E-commerce-Microservices-Containerization/blob/main/runnig%20services.png)
 
