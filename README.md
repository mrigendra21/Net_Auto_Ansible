# Network Automation through Ansible

This repo contains some sample code to automate the basic mandatory configs as per the campus design CVD guide. CVD guide can be accessed here:
https://www.cisco.com/c/dam/en/us/td/docs/solutions/CVD/Campus/CVD-Campus-LAN-WLAN-Design-Guide-2018JAN.pdf

In order to setup your ansible environment, you would need to install the ansible in your local machine. Please refer below installation guide as per your machine type:
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

Once the installation is done, then you are all set to play with Ansible.

There are two ways to run the command from Ansible. Either it can be run as an "ad-hoc" command or can be run as "ansible-playbook".

There are the important file which needs to be created to run the ansible-playbook.
1. Inventory file >> this file contains the name of the devices on which you want to execute the commands.
2. Ansible.cfg file >> this file contains the local environment which specifies some specific parameters, like inventory file location, host-key-check validation etc.
3. YAML file  >> This is the playbook file under which you define the tasks that you want to execute. It can be config commands or output commands.

Please refer to the attached files for more details on how all these file looks like.


Note: These playbooks were run in the gns3 environment and should you need to run the same in actual devices, then the devices specifics needs to be taken under consideration. For more details, please refer to the "References.txt" file.
