# Saltbox Community Repo
[![Docs:](https://img.shields.io/badge/docs-docs.saltbox.dev-blue)](https://docs.saltbox.dev)
[![Contributors:](https://img.shields.io/github/contributors/saltyorg/community?color=blue)](https://github.com/saltyorg/Community/graphs/contributors)
[![Lines of Code:](https://img.shields.io/tokei/lines/github/saltyorg/community)](https://github.com/saltyorg/Community)
[![Issues:](https://img.shields.io/github/issues/saltyorg/Community?color=blue)](https://github.com/saltyorg/Community/issues)
[![CI](https://github.com/saltyorg/Community/actions/workflows/community.yml/badge.svg)](https://github.com/saltyorg/Community/actions/workflows/community.yml)
[![Ansible Lint](https://github.com/saltyorg/Community/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/saltyorg/Community/actions/workflows/ansible-lint.yml)
[![License:](https://img.shields.io/github/license/saltyorg/Community)](LICENSE.md)

Community Repository for Unofficial Saltbox Add-ons

### Requirements

- [Saltbox](https://github.com/saltyorg/Saltbox/)

### Documentation

- [Docs](https://docs.saltbox.dev) (WIP)

### Roles

List of roles can be found by running 
```
cd /opt/community && sudo ansible-playbook community.yml --list-tags 2>&1 | grep "TASK TAGS" | cut -d":" -f2 | awk '{sub(/\[/, "")sub(/\]/, "")}1' | sed -e 's/,//g' | xargs -n 1 | sort -u
```

### Contributors
