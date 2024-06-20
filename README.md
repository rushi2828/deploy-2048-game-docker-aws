# DevOps-Project---Create-a-Game-using-Docker-and-Deploy-to-AWS
Steps to deploy game ‘2048’ with docker on AWS.
Prerequisites: 
AWS console account.
Docker account.
1. Create folder name ‘2048’
2. Create Dockerfile to the folder
 
3. Create Dcoker image with command ‘docker build -t 2048-game.
[It creating image taking too long then restart Docker desktop and sign in again]
 






4. Verify image on docker desktop app OR by using command ‘docker images’ in terminal.
 
OR
 

5. Create docker container by using command 'docker run -d -p 80:80 fc6322e31eb6ccc1e0ac72badc2f5d750e2fe911ba4a63fad526b6b5ae7bb74d’
6. Once the container is running then we can verify by going to ‘http://localhost/80’  
7. Go to AWS console and configure ‘Elastic beanstalk’ service and upload dockerfile.
   
8. Click on ‘Submit’ and then it will take few minutes to create instance on AWS  
