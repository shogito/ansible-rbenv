# Ansible Role: ansible-rbenv

[Build Status]
[wercker status]
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


