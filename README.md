Overview
---
`script.yml` is an Ansible playbook that installs Docker and Supervisor, builds a php and Apache Docker image and runs it with a Supervisor config.
Run it with the command:
```
ansible-playbook -i <host>, -u <user> -k -K -e 'ansible_python_interpreter=/usr/bin/python3' script.yml
```
Replace `<host>` with remote server ip (and SSH port if it's not default) and replace `<user>` with remote username.
NOTE: Don't forget the comma after `<host>`
