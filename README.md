# Docker-resume
pre install
- node
- docker

Step to view
1. npm install
2. npm start
3. the website expose to  http://localhost:3000/

Docker 
Build Images
- docker build -t davidleong98/resume:latest .

Run
- docker run -d --name resume -p 3000:3000 davidleong98/resume:latest

Docker Hub
# please use docker login to verify the credential in docker hub
- // docker push {your docker hub name }:latest
- docker push davidleong98/resume:latest