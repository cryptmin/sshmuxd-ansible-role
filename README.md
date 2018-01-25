sshmux
=========

A example playbook and role to deploy sshmux to a debian jessie host. 

Requirements
------------

Ansible requires the remote host to have python

Role Variables
--------------

vars/main.yml - Main configuration variables. 


Dependencies
------------

N/A

Example Playbook
----------------

	---
	- hosts: all
	
	  roles:
	    -   sshmuxd


License
-------

BSD

Author Information
------------------
Ash Palmer <ash.palmer@cryptmin.net>
