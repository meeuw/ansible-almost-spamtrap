Role Name
=========

My mail configuration; which is almost a spamtrap.

Requirements
------------

Fedora

Role Variables
--------------

    almost_spamtrap_domain: example.com
    almost_spamtrap_smtp: smtp.example.com
    almost_spamtrap_smtp_user: user@example.com
    almost_spamtrap_smtp_password: password123
    almost_spamtrap_email: user@example.com
    almost_spamtrap_mailboxes:
    - email: user1.example.com
      user: user1
    - email: user2.example.com
      user: user2
    almost_spamtrap_blacklist:
    - info@example.com
    - spam@example.com

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: meeuw.almost-spamtrap, x: 42 }

License
-------

GPL-3

Author Information
------------------

dick@mrns.nl
