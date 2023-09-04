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

I am a master student in Computer Science at the [Northeastern University](https://www.northeastern.edu/). I am looking for the internship for 2024 spring/summer.

# 🔨 Projects
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

# 💻 Internships
- *2023.05 - 2023.09*, DevOps Intern, [Jaguar Land Rover](https://github.com/), Portland, U.S.
- *2023.01 - 2023.05*, Teaching Assistant, [Northeastern University](https://www.northeastern.edu/), Seattle, U.S.




