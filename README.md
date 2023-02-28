# Ansible playbook with roles to deploy jenkins in Ubuntu host

## To install Jenkins

### Clone the repository as shown below and get into it

```
git clone https://github.com/saravana1900/ansible-jenkins.git
cd ansible-playbook-jenkins
```

### Modify / Update jenkins-hosts file with your Target Ip-address

```
# Replace the ip-address (target machines ip where jenkins has to be installed ) in the following line as per your requirement

jenkins_master ansible_host=10.0.1.10
```

### Run the playbook to install Jenkins in th target server
```
ansible-playbook -i jenkins-hosts jenkins.yml
```

### To uninstall jenkins from target machine run the playbook as shown below

```
ansible-playbook -i jenkins-hosts jenkins-uninstall.yml
```

