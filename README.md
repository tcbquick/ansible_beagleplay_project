
# Ansible BeaglePlay Project

This repository contains Ansible playbooks and scripts to configure and manage a BeaglePlay device running Debian Bookworm. 
Below are the implemented features:

1. Install Docker and Local Registry.
2. Add specified users to the Docker group.
3. Install Docker on specified hosts.
4. Set up Docker Swarm with managers and workers.
5. Install mail support and configure cron jobs for backups.
6. Deploy an Nginx website to show backup statuses.

resulting from my request on chatgpt:
can you build me a git repository folder and help me create several files based on my following requirments. 1.  add a README.MD file that contains a continuously accumulated transcript of my requests. 2. add a bash install script to install ansible on my BeaglePlay arm device that is running Debian bookworm without using the preferred python pip install method. 3. create an ansible-playbook to install docker and a local registry on port 5555 on this BeaglePlay device that I will be using as my ansible controller using the user name ansible that will need access to use the docker group. 4. create an ansible-playbook to implement the following list of docker users with access to the docker group. ansible, arduino, omada, venus. 5. create an ansible-playbook to install docker on the following list of host devices, hostname1 Main-Con-troller, hostname2 Main-Con-sole, hostname3 Main-Con-nection, hostname4 Swarm-Client-01, hostname5 Swarm-Client-02. 6. create an ansible-playbook to setup all the host devices as a docker swarm all using the local repository from my BeaglePlay where only hostname4 and hostname5 are swarm workers the rest being managers. you should also know that BeaglePlay is hostname0 ansible-Con-troller. 7. create an ansible-playbook to install mail support on all devices for cron jobs to use after you create ansible cron jobs to backup all users home directory to run everyday at 03:01 for all users on all devices. 8. create all necessary html and code deploy an nginx wesite and webpage to show the state of all the backup file created by the cron jobs that we produced.  
