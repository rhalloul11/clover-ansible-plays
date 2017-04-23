
##Docker Deployment

- Requires Ansible 1.2 or newer
- Expects CentOS//Ubuntu hosts

This playbook deploys docker which is an open platform for developers and sysadmins to build, ship, and run distributed 
applications. To use, edit the hosts file to include the names or URL of the servers you want to deploy

####Run the playbook

   &emsp;   `ansible-playbook -i hosts site.yml`


CentOS vagrantfile for testing the playbook
