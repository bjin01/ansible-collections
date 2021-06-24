# ansible-collections
## example: __zookeeper__ 

The inventory file has two types of linux distros: Debian/Ubuntu and SUSE because I have a mixed environment. The group zookeepers is holding the SUSE distro hosts.
The role zookeeper and the tasks are taking care of both distros.

To run the playbook zookeeper:
```sudo ansible-playbook zookeeper_ubuntu.yaml -i inventory --ask-become-pass```



