# Ansible Role: Inspection role

## Tools:

    - htop
    - iotop
    - strace
    - sysstat
    - dstat
    - lsof
    - iputils-ping
    - telnet
    - dnsutils
    - tcpdump
    - iptraf

## Example Playbook

    - hosts: servers
      roles:
         - { role: bezrukovp.inspection }

## License

MIT
