# inception

The ***inception*** project is a 42 system administration assignment where I created a complete web development environment using **Docker** and **docker-compose**. The goal was to set up a small infrastructure composed of different services under specific rules, building each service in its own dedicated container using **Docker**.

What I had to do:
* Set up a Docker infrastructure with:
  * An NGINX container with TLSv1.2 or TLSv1.3
  * A WordPress container with php-fpm
  * A MariaDB container
  * Volumes for the WordPress database and website files
  * A docker-network to connect the containers
* Configure each service with:
  * Custom Dockerfiles (no ready-made images)
  * Environment variables
  * Specific network rules
  * Persistent volume management
* Ensure service stability and data persistence

To achieve this, I had to:
* Write efficient **Dockerfiles** for each service
* Configure NGINX with SSL/TLS security
* Set up WordPress with php-fpm
* Establish MariaDB with secure configurations
* Manage data persistence through Docker volumes
* Create a robust docker-compose.yml file

What I Learned:
* Docker containerization principles and best practices
* Service orchestration with docker-compose
* System administration and network configuration
* Security considerations in web infrastructure
* Database management and persistence
* Environment variable usage and security

Inception was a challenging project that taught me the fundamentals of containerization and modern web infrastructure deployment, providing hands-on experience with tools used in professional environments.