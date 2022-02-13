# Ansible Stack Training

Virtualbox VMs for ansible training

- 3 VirtualBox VM's running Centos 9 (all upgrades made on 20220217).
- Guest additions installed.
- User root - pass: osboxes.org
- User ansible - pass: ansible
- SSH parity configured with ansible user.
- Hostnames configured:
  - Hosts: `ansible-controller`, `ansible-target1`, `ansible-target2`.
  -  `/etc/hosts` configured.
  -  Host-Only network configured with ip 192.168.56.x.
- Ansible installed on ansible-controller, using pip with scope `--user`.

## Download OVA image
You can download my OVA template [here](https://my.pcloud.com) - * I will update the link soon as pCloud get back to work. :/
