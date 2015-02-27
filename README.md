# Ansible Role: ansible-rbenv
[![Build Status](https://travis-ci.org/shogito/ansible-rbenv.svg?branch=master)](https://travis-ci.org/shogito/ansible-rbenv)
[![wercker status](https://app.wercker.com/status/2e30a80cb3513916928c3818fbb18d5d/s "wercker status")](https://app.wercker.com/project/bykey/2e30a80cb3513916928c3818fbb18d5d)
### 要求
none

### Role Variables
rbenvをインストールするユーザ
```
ANSIBLE_RBENV_RBENV_USER
```
rbenvをインストールするロケーション
```
ANSIBLE_RBENV_RBENV_USER_HOME
```
rbenvでインストールするRuby Version
```
ANSIBLE_RBENV_RUBY_VERSION
```

### Example Playbook
```
- hosts: all
  vars:
    ANSIBLE_RBENV_RBENV_USER: root
    ANSIBLE_RBENV_RBENV_USER_HOME: /root 
    ANSIBLE_RBENV_RUBY_VERSION: 2.2.0
  roles:
    - { role: shogito.rbenv }
```

### License
MIT / BSD

### Author Information


