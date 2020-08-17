KVM role
=========

Povisioning KVM Hypervisor, and VMs.

Role Variables
--------------

-   libvirt_folder     - define libvirt folder  
-   image_pool_dir     - define folder to store base image 
-   image_pool_name    - define pool name 
-   image_base_dir     - define dir with base image 
-   image_base_name    - define name of base image
-   image_custom_name  - define name of image for deployment
-   db_user_host       - specify any valid host for db_name
-   vm_folders         - define dictionary with folders for vm01/02
-   vm_images          - define dictionary to folders for vm01/02 custom images
-   image_base_url     - define url to download base image 
-   libvirt_uri        - define domain to use as default 
-   root_pass          - define password to vms  
-   host01             - define host name  
-   host02             - define host name     
-   images             - define name of image folder/pool 


License
-------

BSD-3-Clause (default)


Author Information
------------------

Oleksandr Kyktenko
