# DevOps Ansible Playbooks

## Step 1: Install Ansible on AWS Ubuntu EC2 instance
	$ sudo apt update
	$ sudo apt install software-properties-common
	$ sudo apt-add-repository --yes --update ppa:ansible/ansible
	$ sudo apt install ansible
	$ sudo ansible --version

	Take a screenshot and name file as ansible_install.jpg

## Step 2: Run sample PlayBook1.yml
	//Download PlayBook1.yml
	$ sudo wget https://devops-f2021.s3.amazonaws.com/PlayBook1.yml
	$ sudo ansible-playbook PlayBook1.yml

	Take a screenshot and name file as PlayBook1.jpg

## Step 3: Run barebones_ansible.yaml
	//Download barebones_ansible.yaml
	$ sudo wget https://devops-f2021.s3.amazonaws.com/barebones_ansible.yml
	$ ansible-playbook barebones_ansible.yml

	Take a screenshot and name file as barebones_ansible.jpg
