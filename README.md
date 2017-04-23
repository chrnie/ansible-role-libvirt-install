# Ansible Role: libvirt install

This ansible role install libvirt daemon


## Requirements

None.


## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    libvirt_state: latest

possible values: latest, present, absent

    libvirt_packages:
      - qemu-kvm
      - bridge-utils
      - libvirt-daemon
      - virtinst

define packer version


## Dependencies


## Example Playbook

    - hosts: all
      roles:
        - chrnie.libvirt-install


## License

Apache License 2.0

## Author Information

Created in 2017 by Christoph Niemann, https://github.com/chrnie
