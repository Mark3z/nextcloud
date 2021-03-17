[![CircleCI](https://circleci.com/gh/tide34/nextcloud.svg?style=svg)](https://app.circleci.com/pipelines/github/tide34/nextcloud)

### Manual how to run nextcloud application quickly:  
  
Run next commands:  
  
0) Edit /etc/hosts file. Insert following line in the end of file:  
   `127.0.0.1	cloud.example.com`
    
1) Clone this repository:  
   git clone https://github.com/tide34/nextcloud.git  
  
2) Up all containers:  
   docker-compose up --build -d  
  
3) Wait for **at least 1 minute** after docker-compose command output that all containers had ran.  
  
4) Open in brouser following link:  
   https://cloud.example.com:8080  
  
5) Login into account as administrator with next credential:  
   **Username:** gleb  
   **Password:** Aa1234   
   To **change** default administrator **username** edit nextcloud_admin_user.txt file, **password** edit nextcloud_admin_password.txt file.  
  
6) Stop all containers:  
   docker-compose stop  
  
7) Remove all containers:
   docker-compose rm  
