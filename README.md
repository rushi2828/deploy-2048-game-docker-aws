# DevOps-Project: Deploy-2048 Game using Docker and AWS
Steps to deploy game ‘2048’ with docker on AWS.
Prerequisites: 
AWS console account.
Docker account.
1. Create folder name ‘2048’
2. Create Dockerfile to the folder
 ![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/a13342e8-4c00-4849-a80e-64082fd4ac32) 
3. Create Dcoker image with command ‘docker build -t 2048-game.
[It creating image taking too long then restart Docker desktop and sign in again]
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/3618c61e-0c11-427e-acf5-046f6f10c8db)
4. Verify image on docker desktop app OR by using command ‘docker images’ in terminal.
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/ed085b4e-528f-4e59-8c0d-61bb65973968)

OR
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/30af4439-bb20-46b8-9165-cd7f6f021530)

5. Create docker container by using command 'docker run -d -p 80:80 fc6322e31eb6ccc1e0ac72badc2f5d750e2fe911ba4a63fad526b6b5ae7bb74d’
6. Once the container is running then we can verify by going to ‘http://localhost/80’ 
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/6d77c703-b5aa-47a4-b4c1-cf3980deea60)

7. Go to AWS console and configure ‘Elastic beanstalk’ service and upload dockerfile.
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/597240eb-86d0-4848-8310-fd231fd486dd)
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/7dc3d04b-f5ee-41d3-96bd-0b220f690c90)
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/6d602940-eb71-4304-9594-55edbd49b19a)

8. Click on ‘Submit’ and then it will take few minutes to create instance on AWS
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/b51867c8-399b-4346-816a-6832dde92aa8)
![image](https://github.com/rushi2828/Create-a-Game-using-Docker-and-Deploy-to-AWS/assets/33669698/a913e9fc-d5f9-43bc-91ee-4a72d6890c17)
  
