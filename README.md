# spring-ai-with-rag

## Installation

Step 1 — Create PGVector DB
Run docker-compose.yml file to create PGVector Database, it will create the necessary extension and create the table

Dockerfile.pgvector, this is required to install the necessary extension.

Note — it’s a postgress SQL DB but with pgvector plugin, so we need this file

Step 2 — Run Ollama locally
Download Ollama and run any model as per your machine capacity

Step 3 - Launch Spring Boot application

Step 4 - Test via postman or curl 
example: http://localhost:9191/chat/chat-without-advisor?message="I need a car service and i have only 1010 CHF"