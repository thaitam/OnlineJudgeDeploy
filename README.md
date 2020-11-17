## Install Docker on Ubuntu  
    ```bash
    sudo apt update
    sudo apt upgrade
    sudo apt install docker.io
    ```
## Download source code
    ```bash
    git clone https://github.com/Greenhat1998/OnlineJudgeDeploy
    ```
## Login as root and setup OJ
    ```bash
    sudo passwd root
    su -
    cd /home/{your_user}/OnlineJudge
    apt install docker-compose
    docker-compose up -d
    ```
# DONE!!!
