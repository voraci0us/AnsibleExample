This is an example Ansible playbook written for Hack@UCF's Plinko University workshop series in Spring 2024.

The `ansible.cfg` specifies the location of the inventory file `inventory.ini`.
The `inventory.ini` file defines the IP address for the host we are configuring and authentication details (username, location of private key).

The playbook can be run with `ansible-playbook playbook.yml`.
The playbook is written for Ubuntu 22.04 and installs Apache2 with PHP.
It plants a static web page and a webshell, creates user accounts, and sets an insecure sudoers configuraion.
