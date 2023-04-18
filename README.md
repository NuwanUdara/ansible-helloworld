# Ansible Playbook

## Description

## Usage

1. Install Ansible on the node

2. Create your Playbook in YAML format including targets, tasks and variables.

3. Run the playbook.
   
4. Ansible will connect to the target host and report the changes.

```` bash
ansible-playbook  playbook.yml
````
You can also use, -v flag to get command line outputs if you need to see what exactly is happening.
```` bash
ansible-playbook -v playbook.yml
````
