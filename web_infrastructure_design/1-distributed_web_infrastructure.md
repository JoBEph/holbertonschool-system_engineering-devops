![Exercice 1](Diagram/Exercice%201.png)


 **User Request**: The process begins when a user sends a request to access a website (`www.foobar.com`).

**DNS Resolution**: The domain is translated into an IP address via the DNS system.

**Load Balancers (HAProxy)**: The request passes through two load balancers, which distribute traffic to prevent overload and improve availability.

**Web Servers (Nginx)**: The request reaches Nginx web servers, which handle static and dynamic content.

**Application Servers**: The request is processed by the application, executing necessary operations.

**Databases (MySQL)**: If data is needed, the request is sent to MySQL database, protected by a firewall and secured with SSL.

**Response to the User**: The processed data is sent back to the user through the same optimized and secure system.