nginx_setup
=========

This role will :
    1. Configure nginx to serve a static webpage
    2. Ensure the necessary directories are present for the webpage
    3. Copy a sample index.html to the appropriate directory on the server

Requirements
------------

Have ansible setup on hosts you want to run this role on.  It should run like any other role.

Role Variables
--------------

This role uses 1 variable, in ./vars/main.yml , named _web_page_content.  This variable has the html content that is shown on the webpage

Dependencies
------------

No dependencies

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
Greg Smith
+380 97 546 5994

