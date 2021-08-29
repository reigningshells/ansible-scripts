# Install Guacamole on Ubuntu

Simple playbook to update Ubuntu to the latest release and install Guacamole.  Uses Apache as a front end to more easily manage SSL and logs.

When running the playbook completes, you will be able to access Guacamole at https://your.site.com/access/

## Note 

Before using, update hosts file and files/user-mapping.xml

## Execute

ansible-playbook --private-key /path/to/privatekey install_guac.yml
