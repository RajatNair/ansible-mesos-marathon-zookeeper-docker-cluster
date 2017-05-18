 # Ansible Playbook to setup a cluster of Mesos masters with Marathon and Zookeeper and Mesos slaves with Docker on CentOS7


Installation
-------------
 ```bash
 ansible-playbook -i hosts.yml site.yml
 ```


License
-------
Apache License


Inspired by
-----------
1. [ansible-marathon](https://github.com/AnsibleShipyard/ansible-marathon)
2. [ansible-zookeeper](https://github.com/AnsibleShipyard/ansible-zookeeper)
3. [ansible-mesos](https://travis-ci.org/AnsibleShipyard/ansible-mesos)