Role Name
=========

WordPress deployment in separete vms used KVM hypervisor

Using this role you will be able to install:

 - MySQL DB (databases version 5.7) in docker container
 - nginx server with listening 80 port on kvm-host, and balance trafic between vms
 - wordpress in docker container

Requirements
------------

 The Role deployed on Ububtu 18.04, with ansible 2.9.10.
     

Dependencies
------------

There are no any dependencies you need to worry about

Run
----------------
Before you run dev-kvm.yml, set host in inventory file. 

run role:

ansible-playbook dev-kvm.yml


License
-------

BSD-3-Clause (default)

Author Information
------------------

Oleksandr Kyktenko 