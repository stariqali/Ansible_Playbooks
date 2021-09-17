# Ansible_Playbooks
Purpose of these playbooks is to assist with the day to day F5 BIGIP related activities 
These playbooks were tested using Ansible version 2.19

Before starting please modify the inventory/hosts file to update device information/ IP addresses

Also, edit the group_vars/my_dg/vault.yml file with the appropriate credentials
  Encrypt the file using the following command 
  #ansible-vault encrypt group_vars/my_dg/vault.yml

To run a playbook with ansible vault use the following command
  #ansible-playbook myplaybook.yml --ask-vault-pass
  
Review K64450989 for more information on F5 BIGIP and Ansible vault configuration
