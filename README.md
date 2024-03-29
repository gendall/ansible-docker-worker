# Docker Worker

A role to join a Docker Swarm Worker to a Swarm and store the new node ID under the `docker_node_id` variable.

## Usage

Include this role in a playbook using a [requirements.txt](https://galaxy.ansible.com/docs/using/installing.html#installing-multiple-roles-from-a-file) file.

### Example playbook

```yaml
- hosts: worker
  roles:
    - worker
```

## Deployment

This role will be automatically built and deployed to [Ansible Galaxy](https://galaxy.ansible.com/gendall) when a [Semver](https://semver.org) tag is pushed to the repo.
