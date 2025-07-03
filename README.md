#  Ansible Server Configuration Project
This project uses Ansible to automate the configuration of a Linux server for web hosting and basic security.

##  Technologies Used
- Ansible
- YAML
- Ubuntu (WSL)
- Apache Web Server
- UFW (Firewall)

##  Objective
Automate the following tasks on a target server:
- Install and start Apache web server
- Create a sudo user (`devopsuser`)
- Set timezone to `Africa/Nairobi`
- Configure firewall (UFW) to allow SSH and HTTP traffic only


##  How to Run
1. Clone the repo  
2. Update `inventory.ini` with your server IP or use `localhost`
3. Run:
ansible-playbook -i inventory.ini site.yml --ask-become-pass


