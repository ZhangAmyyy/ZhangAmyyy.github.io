---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a master student in Computer Science at the [Northeastern University](https://www.northeastern.edu/). I am looking for the 2025 SDE full-time roles.

# 💻 Internships
- *2024.08 - 2024.12*, Software Engineer Intern, [Monte Rosa Therapeutics](https://www.monterosatx.com/), Boston, MA.
  + Designed and implemented an ***AI-driven bio-research search platform backend*** using **Python** and **Flask**, leveraging vector search and **RAG** architecture with **LLM** embeddings to automate insight extraction from search results, cutting manual data retrieval and analysis time by up to 25 hours per week
  + Enhanced query flexibility by integrating up to 8 different queries into a single request through **GraphQL APIs**, enabling dynamic and adaptable queries to fit the company’s evolving research needs
  + Eliminated repeated external API calls by indexing and aggregating data in **OpenSearch**, allowing direct queries during user searches, reducing response time from 200ms to 80ms, and mitigating API rate-limiting issues
  + Redeployed 10+ Lambda functions to resolve dependency size limitations, using **AWS** with Cognito, S3, Athena, DynamoDB, and Amplify to build a serverless, highly available architecture and improve deployment efficiency
- *2024.05 - 2024.08*, Software Engineer Intern, [Roche](https://www.roche.com/), Santa Clara, CA.
  + Enhanced a ***microservices DNA sequencing RESTful backend service*** with **Java**, **Spring Boot**, and **Maven**
  + Reduced data analysis service downtime by redesigning the log transfer process with asynchronous handling, utilizing **Redis** and Spring **Async** for efficient task processing, and implementing cron jobs to manage high-traffic periods, enabling real-time cross-device data transfer for parallel analysis
  + Optimized **RabbitMQ** routing keys and redesigned the message queue to effectively decouple and segregate high-volume health ping messages, reducing messaging latency by 20% and preventing message queue deadlocks
  + Developed a flexible multi-input tracing tool by integrating Logstash for local log and message collection, **Elasticsearch** and **Kibana** for quick filtering and analysis of high-volume logs and messages, and **PostgreSQL** for filtered and archival-worthy data storage, significantly improving event traceability and debugging efficiency
  + Collaborated with the testing team to refactor log management **unit tests**, cutting daily test time by 100 minutes
- *2023.05 - 2023.09*, DevOps Intern, [Jaguar Land Rover](https://www.jaguarlandrover.com/), Portland, OR.
  + Migrated ***Advanced Driver Assistance System*** from on-premises to **Kubernetes** (GKE) on **GCP** to realize automatic demand-based scaling, reducing cloud infrastructure costs by 20%
  + Enhanced migration efficiency and maintained compliance by utilizing **Docker** and employed **Kaniko** to securely build images without exposing secrets to the Docker Daemon
  + Reduced deployment delays by automating the **CI/CD pipeline** with **GitHub Action** and **Terraform**, resolving cluster connectivity issues for smooth Kubernetes access, while adhering to **agile** practices for continuous delivery
- *2023.01 - 2023.05*, Teaching Assistant, [Northeastern University](https://www.northeastern.edu/), Seattle, WA.
  + Be the TA of Object-Oriented Design. Teach a class of 60 students, and support instructor in teaching.
- *2022.04 - 2022.08*, Software Engineer Intern, [Wudazhongxin](http://www.wudazhongxin.com/), Hybrid.
  + Developed a ***RESTful backend for an audit document management system*** using **Gin**, integrating **JWT** and **OAuth2** for secure, role-based access, supporting 50TB+ high volumes of long-term data
  + Optimized inter-service communication with **gRPC**, cutting latency by 53% and boosting document workflow
  + Designed a hybrid storage solution using **MySQL** for metadata indexing and S3 for document storage. Utilized **DBML** and SQLC-generated **Go** interfaces to ensure efficient metadata retrieval and data integrity

# 💻 Projects
- [Film Gallery](https://github.com/ZhangAmyyy/film_gallery): 
This is a movie review website that allows users to search for movies and view detailed information, including plot summaries, cast, and user reviews. In terms of the technical implementation, we not only used traditional front-end frameworks but also incorporated external open-source APIs as our backend database. AWS services were employed for CRUD operations and page delivery. Ultimately, the application was containerized into a Docker image and deployed on Google Kubernetes Engine. Throughout the development process, we followed a CI/CD pipeline and utilized GitHub branch management to facilitate collaborative development across multiple environments.
  + CI/CD: CircleCI, GitHub Workflows
  + Front-End: React
  + Cloud & Infrastructure: AWS, GKE, Terraform
  + Containerization: Docker
  + Notifications: Slack
- [Distributed Projects](https://github.com/ZhangAmyyy/distributedproject):
This is an online shopping mall built on a distributed microservices architecture. The entire application is divided into four core modules, each responsible for different functionalities and services, enabling high scalability and flexibility. Technical Stack Summary:
  + ASP.NET
  + Event-Driven Architecture
  + Ocelot API Gateway
  + RabbitMQ
  + NoSQL Databases (MongoDB, Redis)
  + Relational Databases (PostgreSQL, SQL Server)
- [Cloud based Serverless Album](https://github.com/ZhangAmyyy/Cloud-based-Serverless-Album):
This is a photo-sharing platform that allows users to share and browse photos within a cloud-based service. Technology Stack Summary:
  + AWS Cloud Development Kit (CDK)
  + AWS CloudFormation
  + API Gateway
  + AWS Lambda
  + DynamoDB
  + AWS S3
  + AWS Cognito (CIAM)
- [Book Store](https://github.com/ZhangAmyyy/bookstore):
This is an online bookstore for shopping, allowing customers to browse product details, select items, place orders, and view their order history. The project leveraged the following technologies:
  + Front-End: Angular
  + Back-End: Spring Boot
  + Database: MySQL
  + API Development: RESTful APIs, Spring Data JPA, Spring Data REST
  + Authentication and Authorization: OAuth2, OpenID, JWT
  + Web Design: HTML, CSS, JavaScript/TypeScript
- [Chat App](https://github.com/ZhangAmyyy/chatApp-React-Native): 
This is a Mobile chat application that enables users to exchange text messages and images with other users as well as within group chats. The primary technology stack used for this project includes：
  + Front-end: React Native
  + Back-end: Firebase
  + Data Validation: Validate.js
  + State Management: React Hooks, Redux
  + Database: Firestore
  + UUID Generation: npm uuid package
- [Warehouse Management System](https://github.com/ZhangAmyyy/warehouse-Spring-Vue): 
This is a Full Stack Warehouse Management System. The system allows administrators to grant different levels of permissions to various personnel, enabling fine-grained control over access and actions. Depending on their permissions, users can perform various operations, including inventory input (inbound) and output (outbound), facilitating real-time updates of product stock levels. It utilizes the following technologies:

  + Front-End: Vue.js, Axios, Element UI
  + Back-End: Spring Boot, Spring MVC, MyBatis(Plus)
  + Database: MySQL
  + API Testing: Postman

# 💻 Publications
- *A Novel Diffusion Model for Pairwise Geoscience Data Generation with Unbalanced Training Dataset*, Junhuan Yang, **Yuzhou Zhang**, Yi Sheng, Youzuo Lin and Lei Yang. ***AAAI2025***

- [*Enhanced AI for Science using Diffusion-based Generative AI-A Case Study on Ultrasound Computing Tomography*](https://dl.acm.org/doi/abs/10.1145/3649476.3660360), Junhuan Yang, Yi Sheng, **Yuzhou Zhang**, Hanchen Wang, Youzuo Lin, Lei Yang. ***GLSVLSI2024***

- [*On-Device Unsupervised Image Segmentation*](https://arxiv.org/abs/2303.12753), Junhuan Yang, Yi Sheng, **Yuzhou Zhang**, Weiwen Jiang, Lei Yang. ***DAC2023***