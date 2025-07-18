# my-ansible

This Ansible playbooks performs the following tasks:

1. Removes Oracle JDK 1.8 and installs OpenJDK 17 from the official source
2. Installs the latest stable version of Nginx from the official Nginx repository
3. Creates an index.html file that displays the server's IP address (using Ansible facts)
4. Configures Nginx to serve the index.html file
