# docker-tls
This playbook is to set up a server (CENTOS7) with docker TLS installed and running on port 2376

Role Name
=========

Before running the playbook
- Create hosts file with Server name inside
```
echo "[hosts]
"dds_name" >> hosts
```

TO RUN PLAYBOOK
```
ansible-playbook playbook.yml -i hosts -u root --extra-vars "dds_name=<> dds_host=<ip>"
```
dds_host = the IP of server
dds_name = server domain name
