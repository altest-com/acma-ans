acma-ans
=========

![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)

Configuration files for automate deployment of the ACMA project using Ansible.

```bash
sudo apt install python3-wheel python3-pip python3-apt
sudo apt install ansible
git clone https://github.com/altest-com/acma-ans
cd acma-ans
cp group_vars/all_.yml group_vars/all.yml
nano group_vars/all.yml # Edit required variables here
bash deploy.sh
```



