Ansible / monit-web
===================

Ansible playbook to setup and monitor your web application via Monit.



Usage
-----

Create an inventory file with the servers that you want to Node.js on or use `$ANSIBLE_HOSTS`.

    ansible-playbook -i inventory-file -u root main.yml


Monit
-----

Read docs here: http://mmonit.com/monit/documentation/monit.html


Todo
----

- Make OS agnostic.



License
-------

MIT/X11, Copyright 2013, JP Richardson