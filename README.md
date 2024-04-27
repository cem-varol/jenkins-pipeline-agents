# jenkins-pipeline-agents

A pipeline for adding docker agents to Jenkins master

a) single agent: one node.js image is created
b) multi agent: for n-tier applications(fronetend-backend-DB) seperate images are creates every stage
For intance; for frontend use node based image
             for backend use maven-java based image
             for DB use PostgreSQL based image  

