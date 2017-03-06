#base_hostname

Host customizations are done in this playbook.

1. Public DNS name from route53 is set as host name
2. Bash prompt has been customized to include environment parameter

Gather facts in the play which provisions this role, as this role requires ansible facts for OS info and ip of the machine.
