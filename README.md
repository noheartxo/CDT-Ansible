This Ansible script configures an SMB share, creating the folder on the box and copying a scoring file over to the share. Full Access is given to Domain Admins and Administrators, read permissions are given to Everyone. 

It can be defined in a playbook in a yaml file as such: 
---
- name: Create SMB Share
  roles:
    - windows_deploy_smb

To run the playbook, run the command: 
ansible-playbook -i inventory/ [name_of_playbook.yaml]