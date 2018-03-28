Role Name
=========

This is a Go and gb installation and configuration role in RedHat and Debian systems.

Requirements
------------
No requirement

Role Variables
--------------
There is é  variable in this role:
  - go_download_source: contain the source download url of Go compiler
  - version: conatin the version of the Go compiler by default is 10.1 and can be overrided.

Dependencies
------------
No roles dependancy.

Example Playbook
----------------

This is a simple example of using this role:

    - hosts: all
      roles:
         - { role: WissemChb.go, version: "10.1" }

License
-------

BSD

