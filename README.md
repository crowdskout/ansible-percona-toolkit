ansible-percona-toolkit
=========

Installs percona toolkit and xtrabackup for working with mysql/perconadb

Requirements
------------



Role Variables
--------------

percona_toolkit_repo_version: <version of percona repo  to use>

percona_toolkit_packages: <package list to install from percona repo> 
defaults to: 
  - percona-toolkit
  - xtrabackup
  


Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
        - role: crowdskout.percona-toolkit 

License
-------

BSD

