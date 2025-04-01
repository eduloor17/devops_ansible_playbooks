# DevOps Ansible Playbooks

## Step 1: Install Ansible on Debian GNU/Linux 12 (Raspberry Pi 5 Instance)
### A. System Update
 	$ sudo apt update && sudo apt upgrade -y
	$ sudo apt install -y software-properties-common python3-pip

##### PPA Warning: Raspberry Pi OS (Debian-based) does not support PPAs. Instead of adding the Ansible PPA, install Ansible from the official Debian repository or via pip.

### B. Install Ansible
	$ sudo apt install -y ansible
##### OR, if you need the latest Ansible version, use pip:
	$ pip3 install --user ansible
### C. Verify Ansible Installation
	$ ansible --version
##### Take the first screenshot and paste it in a word document.

### D. Clone the Ansible Playbook Repository
	$ git clone https://github.com/eduloor17/devops_ansible_playbooks.git

## Step 2:Step 2: Run barebones_ansible.yaml to install java, docker and Jenkins
### A. Run barebones_ansible.yaml
	$ ansible-playbook -i localhost, --connection=local ~/devops_ansible_playbooks/tiger/barebones_ansible.yml
##### Take the second screenshot and paste it in a word document.

### B. You can check by enter this: 
	$ java -version
	$ docker –version
	$ sudo systemctl status docker
	$ jenkins –version
	$ sudo systemctl status Jenkins

## Step 3: Run sample PlayBook1.yml
### A. Run PlayBook1.yaml
	$ ansible-playbook -i localhost, --connection=local ~/devops_ansible_playbooks/lion/PlayBook1.yml
##### Take the third screenshot and paste it in a word document.

### B. Check the folder that was created in your home directory 
	$ ls -l $HOME/Desktop/
