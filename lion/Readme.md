# Installing Ansible on Ubuntu
	$ sudo apt update
	$ sudo apt install software-properties-common
	$ sudo apt-add-repository --yes --update ppa:ansible/ansible
	$ sudo apt install ansible

# How to install Ansible on Mac OS X using Homebrew
	-- https://www.toptechskills.com/ansible-tutorials-courses/how-to-install-ansible-mac-os-x-tutorial/
	$ brew install ansible
	
# Ansible Version Check
	$ ansible --version

# Execution
	$ ansible-playbook PlayBook1.yml

# Execution with hosts file in current directory
	$ ansible-playbook -i hosts PlayBook1.yml --check
	$ ansible-playbook -i hosts PlayBook1.yml

# References
- https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installation-guide
- https://docs.ansible.com/ansible/latest/user_guide/index.html
- https://www.youtube.com/watch?v=Z01b9QZG0D0
- https://medium.com/tensult/setting-up-a-mac-using-ansible-3dcf63c1d324
- https://github.com/geerlingguy/mac-dev-playbook
- https://www.youtube.com/watch?v=BeYUQaFS-vg

## YAML Validation
- http://www.yamllint.com/
