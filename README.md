# ansible
Intro:
******

Ansible is a push-based configuration management solution that doesn't require an agent or client to be installed on the nodes. Ansible uses an agentless architecture, which means the nodes it manages don't require any software to be installed on them. The central server initiates contact with the nodes and delivers configuration information without requesting it. 

How does it works:
******************
Ansible uses Python, which is almost always pre-installed on any distribution. Ansible reads information about which machines you want to manage from your inventory, and you can create your own inventory file and define which servers you want to be managed. The control software connects to remote machines over SSH and begins managing them without a lengthy setup process.


After ping from Master,clients/nodes responds:
![image](https://github.com/niveditapa21/ansible/assets/110668073/224a222c-58df-4b76-bfad-3b3ae2756c84)
