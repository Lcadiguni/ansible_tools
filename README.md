# ansible_tools
> **_Disclaimer_** :  
> Those scripts are Ubuntu and Fedora in 24.04 and 41 respective
> The Fedora playbook is functional!
___

## Prepare Workstation

1. Install Git
```bash
sudo apt update && sudo apt install git -y
```
or
```bash
sudo dnf update && sudo dnf install git -y
```

2. Install Ansible
```bash
sudo apt update && sudo apt install ansible unzip git -y
```
or
```bash
sudo dnf update && sudo dnf install ansible unzip git -y
```
3. Clone this repository
```bash
git clone https://github.com/lcadiguni/ansible_tools.git
```

4. Apply the configuration
```bash
ansible-playbook ansible_tools/ubuntu.yml --ask-become-pass
```
or
```bash
ansible-playbook ansible_tools/fedora.yml --ask-become-pass
```
