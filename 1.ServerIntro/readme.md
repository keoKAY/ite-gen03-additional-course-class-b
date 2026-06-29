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

vagrant up # turn on the machine 
vagrant halt # shutdown 
vagrant destroy -f # delete the machine 

vagrant ssh # remote to the machine (vm )
# when you are logged in to the machine , run this command 
sudo apt update && sudo apt upgrade -y 
sudo apt install neofetch -y 
neofetch 
sudo init 0 # to shutdown your machine 

```
