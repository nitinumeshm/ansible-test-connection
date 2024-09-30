# ansible-test-connection
This is to test connection with another machine

## Steps
1. Install Ansible in the host machine
2. Create an EC2 instance
3. Create the following files
    - ansible_hosts
    - ansible.cfg
    - hosts.ini
    - playbook.yml
4. Run the following command in the shell prompt
     ### ansible-playbook -i hosts.ini playbook.yml
