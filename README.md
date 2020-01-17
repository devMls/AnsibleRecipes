# AnsibleRecipes
Collection of ansible recipes

# Usage
Fist of all install Ansible in CentOs:
>sudo yum install ansible

Second install Git
>sudo yum install git

Maven and java are optional but always a friend
>sudo yum install maven
>sudo yum install java-1.8.0-openjdk

After that clone this repository
>git clone https://github.com/devMls/AnsibleRecipes.git

Start to install!!
>ansible-playbook --connection=local --inventory 127.0.0.1, <playbook_name>.yml
