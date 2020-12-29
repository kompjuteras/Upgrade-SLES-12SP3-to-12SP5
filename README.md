Upgrade-SLES-12SP3-to-12SP5
------------
Ansible playbook for SUSE upgrade from 12SP3 to 12SP5

Simple playbook for the simpe upgrade of SUSE 12SP3 --> SP4 and --> SP5.

Requirements
------------
Ansible server:
- Ansible 2.7+

Target machine(s):
- SSH connection with the sudo access.
- python and python-xml
- Machine connected to a package repository source

Example Playbook
----------------
`ansible-playbook -i ../hosts.inv Upgrade-SUSE12SP3-to-SP5-regular -u machine_username -K -k`

License
-------
No license, use it as you wish.

Author Information
------------------
Darko Drazovic \
LinkedIn: https://www.linkedin.com/in/darkodrazovic \
Personal: https://darkodrazovic.in.rs \
Blog: https://kompjuteras.com \
GitHub: https://github.com/kompjuteras
