# Automate the process of granting SSH access to a group of servers instances to a new developer.

#### Use below given command to Install ansible
pip install ansible

#### Use below given command to add new user and grant SSH access

ansible-playbook -i inventory users.yml -u root --ask-pass
