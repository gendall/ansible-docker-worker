# Docker Worker

A role to join a Docker Swarm Worker to a Swarm and store the new node ID under the `docker_node_id` variable.

## Example playbook

```yaml
- hosts: worker
  roles:
    - worker
```