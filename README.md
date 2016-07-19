# My Linux Workstation Bootstrap

This repo contains ansible playbooks for bootstrapping my Linux Workstations.

## How to run the playbook

* First you will have to install ansible to run the playbook. To install it on a Fedora 24 machine (which I currently use) use `dnf`

```
sudo dnf install ansible
```

* Clone this repo and run `ansible-playbook`

```
git clone https://github.com/Ranjandas/my-workstation && cd my-workstation
ansible-playbook -c local fedora.yml -K
```
