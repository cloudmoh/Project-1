# Project-1
This is sample project 

Commands Used for master Node

 sudo apt update
 
    2  sudo apt install software-properties-common
    
    3  sudo add-apt-repository --yes --update ppa:ansible/ansible
    
    4  sudo apt install ansible
    
    5  ansible --version
    
    6  ssh-keygen
    
    7  sudo cat .ssh/id_rsa.pub
    
    8  cd .ssh/
    
    9  ls
    
   10  cd
   
   11  cd /etc/ansible/
   
   12  ls
   
   13  sudo nano hosts
   
   14  ansible -m ping all
   
   15  sudo nano hosts
   
   16  ansible -m ping all
   
   17  ansible -m shell -a 'ssh-keyscan 172.31.40.139 >> ~/.ssh/known_hosts' localhost
   
   18  ansible -m ping all
   
Commands used for slave node

sudo apt update

    2  cd .ssh/
    3  ls
    4  sudo nano .ssh/authorized_keys
    5  vi .ssh/authorized_keys
    6  sudo nano .ssh/authorized_keys
    7  sudo nano authorized_keys
    8  history

    


