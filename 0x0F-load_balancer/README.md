0x0F. Load Balancer
This repository contains solutions for the ALX project "0x0F. Load Balancer". The project focuses on configuring and deploying a load balancer to distribute incoming network traffic across multiple servers. Load balancing improves the availability and reliability of web applications by ensuring that no single server is overloaded with requests.

Overview
In this project, we set up a load balancer using HAProxy to distribute incoming HTTP requests across multiple web servers. Load balancing helps to achieve high availability and scalability by evenly distributing traffic among the servers. This ensures better response times and prevents any single server from becoming a bottleneck.

Table of Contents
Description
Tasks
Requirements
Installation and Configuration
Usage
Testing
Contributing
License
Description
The main goal of this project is to configure a load balancer that can efficiently distribute incoming traffic across multiple web servers. By using a load balancer, we can achieve better performance, scalability, and reliability for our web applications. The project tasks include setting up HAProxy, configuring it to use a round-robin algorithm, ensuring proper server naming conventions, and enabling HAProxy management via an init script.

Tasks
The tasks for this project include:

Install and configure HAProxy on the load balancer server
Configure HAProxy to send traffic to multiple web servers using round-robin algorithm
Ensure proper server naming conventions ([STUDENT_ID]-web-01 and [STUDENT_ID]-web-02)
Enable HAProxy management via an init script
Requirements
To complete the tasks in this project, you need:

Access to three Ubuntu servers: one for the load balancer (lb-01) and two for the web servers (web-01 and web-02)
Basic understanding of networking concepts and HTTP protocol
Familiarity with Linux system administration and shell scripting
Knowledge of HAProxy and load balancing principles
