upgrade
=========

[![Build Status](https://travis-ci.org/kilerkarol/upgrade.svg?branch=master)](https://travis-ci.org/kilerkarol/upgrade)

Upgrade packages if apt update-notifier

Dependencies
------------

* [kilerkarol.reboot](https://github.com/kilerkarol/reboot)

Example Playbook
----------------

```
  - hosts: servers
    roles:
      - { role: kilerkarol.fail2ban, tag: fail2ban }
```

License
-------

BSD

Author Information
------------------

Karol Kieglerski