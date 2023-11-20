# B-MaC Bakery

[![LinkedIn][linkedin-shield]][linkedin-url]

## Overview

Welcome to the B-MaC repository. This is designed to automate the supply chain management of B-MaC and to give customer-oriented communication.

 B-MaC specializes in delivering high-quality cakes, donuts, cookies, and more to other bakeries and retail customers through an efficient online ordering platform. Our key differentiator lies in offering same-day ordering and next-day delivery, thanks to a strategically located warehouse stocked with fresh ingredients.

## Technologies

- **Spring Boot** with **Gradle**
- **RabbitMQ** for messaging
- **Keycloak** for identity and access management
- **Bootstrap** for web application styling
- **PostgreSQL** for database storage
- **Docker** for containerization

## User Profiles

### 1. Dabbing Doughnut (Customer)

Dabbing Doughnut represents a loyal customer of B-MaC. Enjoying various types of donuts regularly, they appreciate our loyalty points system. Achieving platinum status, Dabbing Doughnut benefits from a 20% discount on all orders. They value the ability to review past orders and easily replicate them.

### 2. Barry (Head Donut Baker)

Barry, the head donut baker at B-MaC, oversees the creation of the products. Managing sales orders until the 22:00 cut-off time, Barry collaborates with Willow, the warehouse manager, to ensure a smooth supply chain process.

### 3. Willow (Warehouse Manager)

Willow manages outgoing orders for ingredients at the warehouse. Handling stock placement based on specific requirements, Willow aims to optimize order fulfillment and dreams of automating the process based on inventory levels.

### 4. Fruit Cake Inc. (Webshop Customer)

Fruit Cake Inc., a new customer of B-MaC, specializes in fruit-infused cakes. Leveraging B-MaC's API for streamlined order processing, they are eager to explore potential data insights regarding order cancellations.

## Functionality

The B-MaC project comprises three main applications, each serving a distinct purpose:

### 1. Clients Application (API Endpoints)

The Clients Application manages interactions with customers and provides various functionalities:

- Account creation and deletion
- Order creation, including the ability to copy from order history
- Order confirmation with loyalty points and discount information
- Order cancellation
- Loyalty level tracking
- Order history retrieval with filtering options
- Batch upload of purchase orders for B2B customers
- Product management for customer administrators

### 2. Warehouse Application (API Endpoints)

The Warehouse API focuses on warehouse management and handles interactions related to ingredients:

- Retrieval of ingredient information
- Automatic fulfillment and response to outgoing orders, generating deliveries
- Updating ingredient stock levels
- Handling new product events
- Delivery confirmation for received ingredients

### 3. Bakery Application (Web Application)

The Bakery Web Application serves the needs of the bakery staff and includes features such as:

- Product creation, including recipe refinement and finalization
- Modification of product details, including ingredients
- Initiating and automating the baking process
- Overview of current products and deactivation of products


## Testing
The project emphasizes testing, including unit tests for price calculation, loyalty levels, and much more. As well as integration tests for the API's

## Configuration and Logging
Configurability is a crucial aspect, covering infrastructure connections, database configurations, queue setups, IAM and IDP configurations, and business-specific settings such as cut-off times and loyalty levels.

Logging is implemented for diagnostic and error-handling purposes, covering scenarios like incorrect API input, database or queue failures, and XML file processing errors.

## Infrastructure
A Docker-Compose file has been created to run the entire application locally. This includes the following components:

- PostgreSQL database
- Keycloak identity and access management
- RabbitMQ messaging queue

You can find the docker-file here:[docker-compose.yml](docker-compose.yml)




<!MARKDOWN IMAGES AND LINKS>
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin
[keycloak-shield]: https://repository-images.githubusercontent.com/11125589/bd31cf00-70f4-11e9-9fb2-4f241568e586
[springboot-shield]: https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=Spring&logoColor=white
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/milandekok
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com



