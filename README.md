# Dockers
  This   Repository is to go through the important Dockers concepts

## 1 - Install Dockers on Ubuntu

   ### 1.1 - Uninstall if older version of dockers is already installed
      sudo apt-get remove docker docker-engine docker.io

   ### 1.2 - Install Docker
      sudo apt-get install docker.io
      
   ### 1.3 - Automate and start docker
      Run Below Commands to setup Docker service to run at startup:
      sudo systemctl start docker
      
      sudo systemctl enable docker
      
    This will install docker on and docker service will be auto started after machine reboot going forward.
    
   ### 1.4 - Check Docker version
    Below command will print the version number of the docker damon installed
      docker --version
      
      in my case its - Docker version 18.09.07, build 2d0083d
