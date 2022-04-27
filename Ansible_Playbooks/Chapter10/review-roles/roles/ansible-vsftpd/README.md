ansible-vsftpd
=========
Example ansible-vsftpd role from Red Hat's "Linux Automation" (RH294)
course.

Role Variables
--------------

* defaults/main.yml contains variables used to configure the vsftpd.conf template
* vars/main.yml contains the name of the vsftpd service, the name of the RPM
package, and the location of the service's configuration file

Dependencies
------------

None.


Example Playbook
----------------

    - hosts: servers
      roles:
        - ansible-vsftpd

License
-------

BSD

Author Information
------------------

Red Hat (training@redhat.com)
