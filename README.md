# Ansible Role: docker_setup

This Ansible role installs and configures Docker on Ubuntu servers.  
It also sets a custom daemon.json for log configuration.

## Requirements

- Ubuntu 20.04 or 22.04
- Ansible 2.9+

## Role Variables

See `defaults/main.yml` for full list.

## Example Usage

- hosts: app
  become: yes
  roles:
    - your_galaxy_username.docker_setup

## License

MIT

Make sure to replace `your_galaxy_username` with your actual GitHub/Galaxy username.
# ansible-role-docker_setup
