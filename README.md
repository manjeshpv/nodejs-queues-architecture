# nodejs-queues-architecture

1. Entire project in single file
2. splitting into 4 folder structure
  - api
  - conn
  - config
  - components
3. Microservices
  3.1 replicating the project to increase user facing api performance
    - keep the project folder structure same
    - move long running tasks to same function in lambda
    - communicate with node-webhooks for developers
    - enable your queue in production
    - Benefits - developers will commit to same repo, version will stay in sync, easy to understand
  3.2 Introduce   
  
  
