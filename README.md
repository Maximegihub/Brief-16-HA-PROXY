# Brief-16-HA-PROXY
DEPLOIEMENT DE HA PROXY ET HESTIA AVEC ANSIBLE VIA CLE SSH (ssh-copy-id -i ~/.ssh/id_rsa.pub user@ip)
# Installer ANSIBLE :
- sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
- sudo apt install gnupg2
- sudo apt-get install python3 python3-pip -y
- sudo pip3 install ansible
- ansible --version

# Déployer vos playbooks
- ansible-playbook -i inventory.ini main.yml
- ansible-playbook -i inventory.ini deploy_hestia.yml
