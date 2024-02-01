# Ansible Setup
## 1) Update the System Package Index
```
sudo apt update
```
## 2) Install Software Properties Common Package
```
sudo apt install software-properties-common
```
## 3) Add the Ansible PPA (Personal Package Archive)
```
sudo add-apt-repository --yes --update ppa:ansible/ansible
```
## 4) Install Ansible
```
sudo apt install ansible
```
## 5) Verify Ansible Installation
```
ansible --version
```