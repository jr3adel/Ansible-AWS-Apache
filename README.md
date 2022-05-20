# Ansible AWS Apache 

This is a simple project about creating EC2 Instances through Ansible Playbooks and installing Apache Server on these EC2s so here are the steps : 

* Configure a playbook for creating ec2 instances with their security groups and VPC Subnets 
* Configure a playbook for installing Apache server on AMI Images
* Configure a playbook for terminating these instances 

Commands for every step : 

* ansible-playbook -i hosts create_ec2.yml
* ansible-playbook -i hosts install_apache.yml
* ansible-playbook -i hosts remove_ec2.yml
