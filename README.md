iptables
=========

A simple iptables role that sets up a firewall.

Role Variables
--------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
    - hosts: servers
      roles:
         - { role: roguh.iptables, iptables_open_dports: [ 80, 443, 22 ] }
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
