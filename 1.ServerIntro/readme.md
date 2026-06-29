## NOTE related to server lesson 

network address 
ip:port 
public-ip:port
Ubuntu
*** 

Requirement: 
- install vagrant 
- install virtualbox 

```bash 
vagrant init 
# update the line 15 box = "ubuntu/jammy64"
vagrant up 


vagrant init "ubuntu/jammy64" 


vagrant init bento/ubuntu-24.04
vagrant up 
vagrant halt # shutdown 
vagrant destroy -f 
vagrant ssh 
# when you are logged in to the machine , run this command 
sudo apt update && sudo apt upgrade -y 

```
