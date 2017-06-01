SuperNAs
=========

Turn your nas4free or FreeBSD in a MediaCenter Cluster

 With SuperNAs you can build a failover Carp+Hast Cluster over two Nas4Free Installations...
 On files directory can be found some scripts i have been changed to improve Failover with CARP+HAST+ZFS Cluster.

Requirements
------------

To be able to set a cluster, you will need ate least two machines with Nas4Free pre-installed.
For hast you will need at leats one disk(same size) on each machines. You can specify that on main vars.

Role Variables
--------------

Soon it will be described here
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

No other roles depency yet

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

This role was create in 2017 by [Igor Brandao](https://isca.space)

