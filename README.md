# fgcp-lab

Ansible deployment script for an FGSP lab.  Minimal or no error correction, this was done quick and dirty while watching Packers vs. Eagles on MNF.

Deployment can be run using locally installed ansible, or can be executed from a docker container.

reporoot:
/admin_password.txt   <- put your admin password here

/ansible <- execute ansible scripts from here if running ansible locally

/ansible/inventory/inventory.yml <- edit the name/ip of your FortiGates
/ansible/inventory/fgsp.yml <- the network setup parameters for the lab.  
