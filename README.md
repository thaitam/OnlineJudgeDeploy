## Install environment on Ubuntu 16.04 LTS  

1. Install packages
    ```bash
    sudo apt install -y python-pip curl git
    pip install docker-compose
    ```

2. Install Docker 
    
    Use ```sudo curl -sSL https://get.daocloud.io/docker | sh```
    
    or  ```sudo curl -sSL https://get.docker.com | sh``` 
  
    More reference at： [https://docs.docker.com/install/](https://docs.docker.com/install/)

## Setting and configing system

1. Use root permission
    ```bash
    sudo passwd root
    su -
    cd ..
    cd home/youruser
    ```
2. Disable processes that are using port 80
    ```
    sudo lsof -t -i tcp:80 -s tcp:listen | sudo xargs kill
    ```
    
3. Clone sources project
    ```bash
    git clone https://github.com/Greenhat1998/OnlineJudgeDeploy
    cd OnlineJudgeDeploy
    ```
    
4. Run docker-compose
    ```bash
    apt install docker-compose
    docker-compose up -d
    ```
