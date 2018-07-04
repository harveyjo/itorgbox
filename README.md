# IT Organization Box. Spin Up an IT Department in 10 Minutes.

This is meant to be a docker package that gives you everything you need to be an effective IT department in one command, in under 10 minutes. Here's what you get. Just deploy it to a server with docker installed behind your firewall and run (or, run it locally).

`docker-compose up --build`

This will start the project at localhost (or, the server's IP, for connecting from other machines on the network). For in-house servers and Windows-based environments, make a Group Policy that pushes DNS rules resolving your custom domains to the various services by portmapping. Manage the whole thing in source for custom branding, integrations, and extentions. Persistent data storage using mounted volumes, centralized database management using phpMyAdmin

example.org -> server.ip
inventory.example.org -> server.ip:3000
cloud.example.org -> server.ip:3001
knowledge.example.org -> server.ip:3002
helpdesk.example.org -> server.ip:3003

# Creating a Distributed Environment

## Wordpress Intranet/IT Department Website at port 80


[title](http://)

## Inventory Management System With Snipe IT at port 3001
`Username: Admin`
`Password: Admin`

[title](http://)

## Self-Hosted Organization Cloud Storage and File Management with OwnCloud at Port 3002
`Username: Admin`
`Password: Admin`

[title](http://)

## Knowledge Base, Help Articles, and Wiki with BookStack at Port 3003
`Username: Admin`
`Password: Admin`

[title](http://)

## Helpdesk Support and Email Ticketing with Brimir on Port 3004
`Username: admin@admin.com`
`Password: password`

[title](http://)


