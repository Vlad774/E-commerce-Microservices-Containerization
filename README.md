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

![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/diagramm.png) 
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/ec2.png) 
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/bitbucket.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/RDS.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/ELB.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/Build%20History.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/CodePipeline.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/test.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/Service_running.png)
