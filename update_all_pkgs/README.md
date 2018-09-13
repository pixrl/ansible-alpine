# Alpine Linux update playbook for Ansible
Designed only for one host for now

#### Configure
Specify your host at line:
`hosts: [YOUR_HOST]`

#### Run
Execute playbook:
`ansible-playbook -K update.yml`

If you made your own inventory file:
`ansible-playbook -i [PATH_TO_INVENTORY_FILE] -K update.yml`

#### Log file
After execution there will be a log file in your `playbook_dir`:
`update.log`
