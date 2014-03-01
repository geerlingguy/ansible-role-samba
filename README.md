# Ansible Role: Samba (SMB)

Installs Samba client and server for RHEL/CentOS 6.x.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: geerlingguy.samba }

Installs the samba server and client, so you can mount cifs shares, and create samba shares, shared printers, etc.

## License

MIT / BSD

## Author Information

This role was created in 2014 by Jeff Geerling (@geerlingguy), author of Ansible for DevOps. You can find out more about the book at http://ansiblefordevops.com/, and learn about the author at http://jeffgeerling.com/.
