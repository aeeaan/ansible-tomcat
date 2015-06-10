correcthorse.tomcat
=========

An ansible role for installing tomcat.

Role Variables
--------------

| Variable				| Default					| Notes				|
| :---					| :---						| :---				|
| tomcat_shutdown_port			| 8005						| 				|
| tomcat_http_port			| 8080						|				|
| tomcat_open_http_port			| false						|				|
| tomcat_ajp_port			| 8009						|				|


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: correcthorse.tomcat }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
