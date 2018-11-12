Jboss_webserver
=========

This role installs a jboss webserver either by downloading the tar from RHN, copying the file from the controller or installing by RPM.

Requirements
------------

* JDK 8(java) (rhel-7-server-rpms).
* java-devel.
* the tar locally.
* RHN access to download the tar.
* the VM with the correct subscriptions (jws-5-for-rhel-7-server-rpms and jb-coreservices-1-for-rhel-7-server-rpms).

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: jboss_webservers
      roles:
         - jboss_webserver
         - jbosswebserver_configure

License
-------

GPLv3

Author Information
------------------

