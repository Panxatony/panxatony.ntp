panxatony.ntp
=========

Configure system ntp

Requirements
------------

    none

Role Variables
--------------

    ntp_timezone: Europe/Berlin
    ntpdate_server: pool.ntp.org

Dependencies
------------


    none


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: panxatony.net, ntpdate_server: 10.0.10.10 }

License
-------

BSD

Author Information
------------------

Lars Hunold
http://macnemo.tv