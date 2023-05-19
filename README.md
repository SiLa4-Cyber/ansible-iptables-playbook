# ansible-iptables-playbook
This ansible playbook is designed to quickly generate iptables rules using a script written in templates/rules.v4.j2
You only need to register the port numbers in the format:

```tcp_firewall: 22,33,44```
