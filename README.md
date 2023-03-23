# ansible-role-docker-swarm-init
### Sample inventory file

```sh
[nodes]
node-1      ansible_host=XXX.XXX.XXX.XXX
node-2      ansible_host=XXX.XXX.XXX.XXX
node-3      ansible_host=XXX.XXX.XXX.XXX
node-4      ansible_host=XXX.XXX.XXX.XXX

[swarm_manager]
node-1

[workers]
node-[2:4]
```
