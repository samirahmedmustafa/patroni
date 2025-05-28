# Patroni ansible playbooks

The repository objective is to introduce highly available postgresql using patroni

Requirements:
- 3 rocky9 linux servers/VMs (as the minimum number of nodes to start ETCD is 3)
- Postgresql built from source code(you can use yum/dnf and disable the postgres deployment role)
- A web server in the ansible server, used as artifactory to fetch packages from
- etcd package in the ansible web server

Thanks to Tim https://technotim.live/posts/postgresql-high-availability/
