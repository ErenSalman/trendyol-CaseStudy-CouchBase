# execute command
ansible-playbook --private-key case.pem playbooks/createCouchBaseCluster.yml -i hosts --verbose
