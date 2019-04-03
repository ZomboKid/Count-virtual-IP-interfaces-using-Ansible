# Count-virtual-IP-interfaces-using-Ansible
This playbook counts virtual IP interfaces (for example - defined by keepalived) and fails when vip interface is up on more than one backend server.<br/>
./group_vars/all - definition of vip interface address and variable "deploy" (which should be set to true if we want to use this playbook).<br/>
./inventory - backend servers IP.<br/>
./start_palybook.sh - shell script to start playbook.<br/>
./start_palybook_with_debugging.sh - shell script to start playbook with debugging.<br/>
