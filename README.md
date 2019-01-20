# ansible-aws-wordpress
This Playbook uses ec2 and rds services to install WordPress site. Apache is used as the webserver and RDS MySQL as the database.
This is supposed to be basically for dev environment.

# Prerequisites:
Make sure to make available below packages in your Ansible Box. Configure boto with required AWS access and secret keys.


* boto
* python >= 2.6
* boto3 >= 1.0.0
* Ansible

# How to use this playbook:

1. Clone this repo.
2. Make sure j2 and playbook.yml stay in the same directory. 
