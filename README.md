=> Folder Structure
Frontend
.gitignore
.dockerignore
Dockerfile

Backend
	.gitignore
.dockerignore
Dockerfile

docker-compose.yml

===================
1. add .gitignore and .docker ignore
2. Dockerfile
Add above two file and docker codes in both frontend and backed

=================
3. Add docker-compose.yml in root which run frontend/backed docker.
Each time we run build and docker-compose file


Command for build and run cocker-compose.yml
# docker-compose up (to build and run docker-compose.yml)

Command to build and run frontend/backend locally
# docker build -t name .
# docker run -p 5147:3000 react-app
