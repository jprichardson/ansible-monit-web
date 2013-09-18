Ansible / monit-web
===================

Ansible playbook to setup and monitor your web application via Monit.



Usage
-----

Create an inventory file with the servers that you want to Node.js on or use `$ANSIBLE_HOSTS`.

if connecting with root:

    ansible-playbook -i inventory-file -u root main.yml

if sudoing:

    ansible-playbook -i inventory-file -K main.yml



Monit
-----

Read docs here: http://mmonit.com/monit/documentation/monit.html



Todo
----

- make OS agnostic
- consider PID file tracking instead
- remove prompt variables for external file



License
-------

MIT/X11, Copyright 2013, JP Richardson