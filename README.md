# Ansible Role: k8s_base

[![Lint](https://github.com/dcjulian29/ansible-role-k8s_base/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-k8s_base/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-k8s_base.svg)](https://github.com/dcjulian29/ansible-role-k8s_base/issues)

This an Ansible role to preform the base setup I expect for kubernetes clusters I manage.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.k8s_base
  src: https://github.com/dcjulian29/ansible-role-k8s_base.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
