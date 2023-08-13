# node-todo-cicd

Run these commands:

 # Install Docker 
`sudo apt-get install docker.io`

 # Install Docker Compose
`sudo apt-get install docker-compose`

 # Add Host user to Dcoker user
`sudo usermod -aG docker $USER`

 # Install JDK for Jenkins  
`sudo apt install default-jdk`

 # Add Jenkins Repository

 `wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -`
 `sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'`

  # Add Jenkins Repository
  `sudo apt update`
  `sudo apt install jenkins`
  `sudo systemctl start jenkins`
  `sudo systemctl enable jenkins`

  # Open Jenkin Url on host machine using 8080 port
   Like-'http://54.172.138.86:8080/'

  # Create Pipe Line 

  ![image](https://github.com/vikashlohiya/php-docker-jenkins/assets/62418120/027e9903-d3aa-45a0-a407-2b8217a6024e)

  Add Github URL

  # In build section you have to check  below option
  GitHub hook trigger for GITScm polling  

  ![image](https://github.com/vikashlohiya/php-docker-jenkins/assets/62418120/dc78d717-ee72-4557-abf7-7d36ac4e5c94)

  # In Pipe line section, you have to select branch where Jenkins file located 
  In Defination option , you have to select  , Pipeline script from SCM

  ![image](https://github.com/vikashlohiya/php-docker-jenkins/assets/62418120/ec8be475-afd7-4d97-a89c-112b2b439ad2)


  


  

