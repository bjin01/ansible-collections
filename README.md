# ansible-collections
## example: __zookeeper__ 

The inventory file has two type of linux distro: Debian/Ubuntu and SUSE because I have a mixed environment.
The role zookeeper and the tasks are taking care of both distros.

To run the playbook zookeeper:
```sudo ansible-playbook zookeeper_ubuntu.yaml -i inventory --ask-become-pass```



