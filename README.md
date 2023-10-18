# Brief-16-HA-PROXY
HA PROXY WITH ANSIBLE

- Installer ANSIBLE
- Créer votre fichier de configuration
- Créer votre fichier inventory.ini
- Créer un rôle pour haporxy
ansible-galaxy init haproxy_role 
- Créer le playbook HAPROXY (haproxy.cfg.j2)
- Créer le playbook HESTIA (deploy_hestia.yml)
- Déployer vos playbooks
- ansible-playbook -i inventory.ini deploy_haproxy.yml
- ansible-playbook -i inventory.ini deploy_hestia.yml
