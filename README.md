Run docker compose up -d --build
this is run the docker-compose.yml in which it builds containers for both frontend and backend in the same docker network then runs the container of nginx which is binded to port 80 of the host machine i.e., port mapping 
now we can run see the frontend on http://localhost and backend on http://localhost/api
