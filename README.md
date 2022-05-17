# 4IT572_ansible
Instalace

sudo yum install git

pip3 install ansible boto boto3

https://github.com/antydex/4IT572_ansible.git

ansible-vault create group_vars/all/aws.yml

ansible-playbook ec2_deploy.yml --ask-vault-pass

scp -i "devops.pem" ./devops.pem ec2-user@ec2-3-82-208-0.compute-1.amazonaws.com:~4IT572_ANSIBLE -> překopírování klíče do aws
