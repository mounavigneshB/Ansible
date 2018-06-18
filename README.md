# Ansible

Create-ec2-instance with existing VPC, Subnet, Security Groups, AMI


###Create Floders
You have create sub-floders and put below files in sub-floders.

Create-ec2-instance -
								 - provision-ec2.yml
								 - ec2-vars/testserver.yml
								 - roles/provision-ec2/tasks/main.yml

###Commnad for run ansible-playbook:
ansible-playbook -vv -i localhost, -e "type=testserver" provision-ec2.yml
