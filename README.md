# ansible_tools
> **_Disclaimer_** :  
> Those scripts are Ubuntu and Fedora in 24.04 and 41 respective
> The Fedora playbook is functional! Ubuntu and Arch Linux in tests
___

## Prepare Workstation

1. Install Git
Ubuntu
```bash
sudo apt update && sudo apt install git -y
```
Fedora
```bash
sudo dnf update && sudo dnf install git -y
```

2. Install Ansible
Ubuntu
```bash
sudo apt update && sudo apt install ansible unzip git -y
```
Fedora
```bash
sudo dnf update && sudo dnf install ansible unzip git -y
```
3. Clone this repository
Ubuntu
```bash
git clone https://github.com/lcadiguni/ansible_tools.git
```

4. Apply the configuration
Ubuntu
```bash
ansible-playbook ansible_tools/ubuntu.yml --ask-become-pass
```
Fedora
```bash
ansible-playbook ansible_tools/fedora.yml --ask-become-pass
```
