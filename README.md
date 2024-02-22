# Web Infrastructure Design

## Learning Objectives
- Network Basics
- Server
- Web Server
- DNS
- Load balancer
- Monitoring
- What is a database
- What's the difference between a web server and an app server?
- DNS record types
- Single point of failure
- How to avoid downtime when deploying new code
- High availability cluster (active-active/active-passive)
- What is HTTPS
- What is a firewall

## Project Requirements
- Draw a diagram covering the web stack you built with the sysadmin/devops track projects
- Explain what each component is doing
- Explain system redundancy
- Know all the mentioned acronyms: LAMP, SPOF, QPS

## Projects
### 0. Simple web stack
On a whiteboard, design a one server web infrastructure that hosts the website that is reachable via www.foobar.com. Start your explanation by having a user wanting to access your website.

Requirements:

You must use:
- 1 server
- 1 web server (Nginx)
- 1 application server
- 1 application files (your code base)
- 1 database (MySQL)
- 1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8
You must be able to explain some specifics about this infrastructure:
- What is a server
- What is the role of the domain name
- What type of DNS record www is in www.foobar.com
- What is the role of the web server
- What is the role of the application server
- What is the role of the database
- What is the server using to communicate with the computer of the user requesting the website
You must be able to explain what the issues are with this infrastructure:
SPOF
- Downtime when maintenance needed (like deploying new code web server needs to be restarted)
- Cannot scale if too much incoming traffic
- Please, remember that everything must be written in English to further your technical ability in a variety of settings.
