# PayFlow - Production-Grade FinTech Platform

**Enterprise patterns for DevOps portfolios**


# Task - Draw the Architecture

Diagram should include: Auth, Wallet, Transaction, Notification, API Gateway, Frontend, DB, Redis, rabbitmq. 

Draft Diagram
![Draft Diagram](tasks/images/draft%20flow.jpg)

## Explain Each Service

**API Gateway Service**:

1. Purpose:  Main entry point for all client request. it handles routing, authentication, rate limiting and monitoring.

2. Ports:
    - PostgreSQL connection variables are established on port 5432
    - Redis connection on port 6379
    - RabbitMQ on port 15672
    - auth-service on port 3004
    - wallet-service on port 3001
    - transaction-service on port 3002
    - notification-service on port 3003

3. Environmental Variables:
    - loaded from .env.example for DB, Redis, RabbitMWQ, JWT, Services, CORS,   Environment (Dev), Email, SendGrid, SMS-Twilio, SSL/TLS for Production, Logging

4. Dependencies (other services/DB/cache):
    - express - a web framewrok for Node.js. Application setup.
    - helmet - sets seurity headers
    - cors - cross-origin resource sharing to allow frontend to call API
    - morgain - HTTP request logger
    - rateLimit - limiting to prevent abuse
    - axios - HTTP client for calling other services
    - Prometheus - metrics collection for health and performance
    - Circuit breaker - to prevent cascading failure
    - User Registration Tracking - Successful and failed signups
    - Money Transfer - counts money transfer for analytics

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
