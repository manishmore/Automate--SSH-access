# Automate--SSH-access

``` Automate -SSH-access ```

Automate the process of granting / revoking SSH access to a group of servers instances to a new developer

To grant SSH access to an existing user:
ansible-playbook -i inventory/ -e "action=grant" playbooks/ssh.yml

To revoke SSH access from a user:
ansible-playbook -i inventory/ -e "action=revoke" playbooks/ssh.yml
