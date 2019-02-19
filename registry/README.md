# Docker Registry
<br>

## Prerequisites

### Infra

- Good to have have two machines. 
- We can either use two VMs or two instances from a cloud provider (AWS), that can communicate with each other. This set up would be more suitable to run through the lab. 

### Docker 

- Log into the two instances and ensure that Docker is installed. 
- Execute **docker info** command to ensure that the user has required permissions. 
- If there is an error, we can switch to **sudo** user and continue.
- A better approach is to add current user to **docker** group using the following command:
```
sudo usermod -aG docker $USER
```
Now, logout and then login. 
<br>

Congratulations! We have successfully setup our environment for this lab.
<br>


## Labs

- 
