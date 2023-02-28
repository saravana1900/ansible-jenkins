# Ansible playbook with roles to deploy jenkins in Ubuntu host

#### clone the repository
```
git clone https://github.com/saravana1900/ansible-playbook-jenkins.git
cd ansible-playbook-jenkins

```
#### change / update the target ip address in jenkins-hosts file

```
jenkins_master ansible_host=10.0.1.10

```

#### To run the playbook follow the 
```
ansible-playbook -i jenkins-hosts jenkins.yml

```

