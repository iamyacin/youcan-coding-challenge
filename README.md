## Coding challenge IV: Save our app from DDos attacks
### Problematic
Haproxy provides a high, fast and efficient availability load balacing and proxying.
We would like to get benefits of its in-memory storage stick table technology to secure our platform by tracking our users activities including malicious ones. 
We would like to introduce haproxy in top level or our web architecture.

### Prerequisites :
[Gide to install Docker](https://docs.docker.com/engine/install/).

[Gide to install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

### How to use this Repo :
1. Clone this Repo
2. If you want to start containers with docker compose use :

      `docker-compose up`

3. If you want to start containers with docker compose use :

      `ansible-playbook ansible-playbook.yaml`
