# ucloud-k8s

Requirements:

- a key to access uCloud machines through SSH. The key location is set in `ansible/ansible.cfg`
- a Tailscale auth key (https://tailscale.com/kb/1085/auth-keys). The Ansible playbook expects it to be in the `tailscale_key` file at the root level of this repo. Can be changed in the "`connect to tailscale`" task, in the `tailscale` role.
- a `hosts.ini` file in the `ansible` directory. See `hosts.ini.example` for the expected roles.