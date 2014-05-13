Variables defined in `vars` is available to included playbooks but
variables included via `vars_files` is not.

Run command
```
ansible-playbook -i inventory site.yml
```
