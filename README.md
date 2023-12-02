# ansible-role-docker-swarm-init
### Sample inventory file

```yaml
nodes:
  hosts:
    node1:
    node2:
    node3:
    node4:

swarm_managers:
  hosts:
    node1:

swarm_workers:
  hosts:
    node2:
    node3:
    node4:
```
