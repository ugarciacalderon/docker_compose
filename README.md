# Docker Compose

It is a Docker tool to define and run multiple Docker container applications using one yaml file to start all our services. 
Docker Compose can be used in Production, Testing and Development environments.

This project contains three folder, default, qa, prod. To start an environment it is necessary to enter the desired directory
Each file contains the definitions of application containers:
- Config Server
- Eureka Server
- Accounts MS
- Cards MS
- Loans MS
- Gateway Server

in this file can be define many instances of each application, and Eureka Server admin de load and balance applications.
