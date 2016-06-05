Repo for bootstrapping an example AWS ECS environment. The only thing you will
need preprepared in AWS is your credentials in either environment variables or
in your .aws/credentials file, and a keypair.

Set the variables to suit your tastes in the vars folder and the playbook, and simply run:

`ansible-playbook playbooks/bootstrap.yml`
