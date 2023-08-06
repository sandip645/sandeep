Clone the GitHub repo:

git clone https://github.com/sandip/Docker-Certified-Associate.git
Build the Docker image:

cd Docker-Certified-Associate/1-basic-docker-commands/
docker build -t sandip/httpd:latest .
List images:

docker images
Run a Docker container:

docker run -d -p 80:80 --name httpd-container sandip/httpd:latest
List running containers:

docker ps
Execute a command inside a running container:

docker exec httpd-container ps aux
Pull an image from Docker Hub:

docker pull sandip/httpd:latest

Push an image to Docker Hub:

docker login
docker push sandip/httpd:latest
Search for images on Docker Hub:

docker search httpd

Show Docker version information:
docker version
Display system-wide information:
docker info
Stop a running container:
docker stop httpd-container
Remove a container:
docker rm httpd-container
Remove an image:
docker rmi sandip/httpd:latest
Log out from Docker Hub:
docker logout
