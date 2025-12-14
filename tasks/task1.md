
# Task - Draw the Architecture

Diagram should include: Auth, Wallet, Transaction, Notification, API Gateway, Frontend, DB, Redis, rabbitmq. 

Draft Diagram
![Draft Diagram](./images/draft%20flow.jpg)

## Explain Each Service

**API Gateway Service**:

- Purpose:  Main entry point for all client request. it handles routing, authentication, rate limiting and monitoring.

- Ports:
    1. PostgreSQL connection variables are established on port 5432
    2. Redis connection on port 6379

- Environmental Variables:

- Dependencies (other services/DB/cache):
    1. express - a web framewrok for Node.js
    2. helmet - sets seurity headers
    3. cors - cross-origin resource sharing to allow frontend to call API
    4. 

**Auth Service**:

- Purpose:

- Port:

- Environmental Variables:

- Dependencies (other services/DB/cache):

**Frontend Service**:

- Purpose:

- Port:

- Environmental Variables:

- Dependencies (other services/DB/cache):

**Notification Service**:

- Purpose:

- Port:

- Environmental Variables:

- Dependencies (other services/DB/cache):

**Shared Service**:

- Purpose:

- Port:

- Environmental Variables:

- Dependencies (other services/DB/cache):

**Transaction Service**:

- Purpose:

- Port:

- Environmental Variables:

- Dependencies (other services/DB/cache):


**Wallet Service**:

- Purpose:

- Port:

- Environmental Variables:

- Dependencies (other services/DB/cache):


## Full Request Trace

- Trace “Send Money” end to end with notes + sequence diagram.
