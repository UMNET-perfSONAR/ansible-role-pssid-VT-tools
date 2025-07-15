# ansible-role-pssid-VT-tools
> Install L2 and L3 Virginia Tech tools on probes

From within the repo directory, run the following command after the probes have been bootstrapped (be sure to modify the hosts file to reflect the IP addresses of the pis):
```
ansible-playbook --ask-vault-pass --ask-pass --ask-become-pass --user <user> --become --become-user root --become-method su --inventory inventory/ playbook.yml
```
