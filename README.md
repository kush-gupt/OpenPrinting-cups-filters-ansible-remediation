# OpenPrinting cups-filters Ansible Playbook Remidiation

Based off the steps outlined in [RHSB-2024-002]([url](https://access.redhat.com/security/vulnerabilities/RHSB-2024-002)), this playbook checks if the system you are running this against has the prerequisites for the exploit to work, and then runs either an HA or non-HA mitigation based on your server scenarios.

This is done through Ansible tags, either
- HA
- non-HA (default)
