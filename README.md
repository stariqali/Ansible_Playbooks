# Ansible_Playbooks
Purpose of these playbooks is to assist with the day to day F5 BIGIP related activities 
These playbooks were tested using Ansible version 2.19
You would still need to modify the inventory/hosts file to update device information/ IP's
Lastly you would need to edit the group_vars/my_dg/vault.yml file with the appropriate credentials
  Encrypt the file using the following command 
  #ansible-vault encrypt group_vars/my_dg/vault.yml

To run a playbook with ansible vault use the following command
  #ansible-playbook <playbook>.yml --ask-vault-pass
