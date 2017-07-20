ansible-role-sonarr
=========

An Ansible role to install Sonarr on CentOS 7


Requirements
------------

CentOS/Red Hat Enterprise Linux 7

Role Variables
--------------

Defaults:

- sonarr_directory = /opt/sonarr/ - directory to install sonarr
- sonarr_user = sonarr - user that will run sonarr
- sonarr_home = /home/sonarr - sonarr_user home folder - sonarr stores configs here

Vars:

- sonarr_prereqs - all sonarr prerequisite packages that need to be installed via Yum
- sonarr_url - sonarr latest release url
- mono_baseurl - mono repo url
- mono_gpgurl - mono repo gpgkey url 

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mujahidhemani.sonarr }

License
-------

GPLv3

Author Information
------------------

Author: Mujahid Hemani
