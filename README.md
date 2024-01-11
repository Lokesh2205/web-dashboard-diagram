# web-dashboard-diagram
Deployment procedures in a block diagram

1. Angular Frontend:

In Angular we will build the packages and store the dist files in Angular/Nginx web server.

2. Python Backend:

We are using Python as backend and it is running on 8000 port. We will be doing reverse proxy to map sub domain with 8000 port. And install ssl to sub domain, to avoid cors origin errors in future.

3. Mysql Database:

We will be using Mysql database for storing the data as secured in server.
