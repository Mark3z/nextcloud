[![CircleCI](https://circleci.com/gh/tide34/lab4-task1.svg?style=svg)](https://app.circleci.com/pipelines/github/tide34/lab4-task1)

### Manual how to run nextcloud application quickly:  
  
Run next commands:  
  
0) Edit /etc/hosts file. Insert following line in the end of file:  
   `127.0.0.1	cloud.example.com`
    
1) Clone this repository:
   `git clone https://github.com/tide34/nextcloud.git`  
  
2) Up all containers:
   `docker-compose up -d`  
  
3) Wait some time before docker-compose command outputs that all containers will be running.  
  
4) Open in brouser following link:  
   `https://cloud.example.com:8080` 
