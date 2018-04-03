# Important: 

  This project is forked from https://github.com/jenkinsci/docker 

# Building

Specified Jenkins version, example: 2.113
  ```
  docker build -t jenkins2.113 --build-arg JENKINS_VERSION=2.113 .
  ```

# Run 
  ```
  docker run -p 8080:8080 -p 50000:50000 jenkins2.113
  ```
  ## Run as deamon (UNIX): add option d
  ```
  docker run d -p 8080:8080 -p 50000:50000 jenkins2.113
  ```
  Run your Jenkins server at: http://<your_server_name_or_ip>:8080
  ## Setup the Jenkins for the first use
  ## Note: admin password is printed in console log
  
