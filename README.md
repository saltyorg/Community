# Saltbox Community Repo
[![Website:](https://img.shields.io/badge/website-https%3A%2F%2Fsaltbox.dev-blue)](https://saltbox.dev)
[![Wiki:](https://img.shields.io/badge/wiki-https%3A%2F%2Fwiki.saltbox.dev-blue)](https://wiki.saltbox.dev)
[![Contributors:](https://img.shields.io/github/contributors/saltyorg/community?color=blue)](https://github.com/saltyorg/Community)
[![Lines of Code:](https://img.shields.io/tokei/lines/github/saltyorg/community)](https://github.com/saltyorg/Community)
[![Issues:](https://img.shields.io/github/issues/saltyorg/Community?color=blue)](https://github.com/saltyorg/Community/issues)
[![Build status](https://appveyor.cloudbox.work/api/projects/status/tyraswwahlldwpnu/branch/master?svg=true)](https://appveyor.cloudbox.work/project/AppVeyor/community/branch/master)
[![License:](https://img.shields.io/github/license/saltyorg/Community)](LICENSE.md)

Community Repository for Unofficial Saltbox Add-ons

### Requirements

- [Saltbox](https://github.com/saltyorg/Saltbox/)

### Install

- [Install](https://wiki.saltbox.dev/Community/Install) (Not ready)

### Wiki

- [Wiki](https://wiki.saltbox.dev/Community) (Not ready)

### Roles

List of roles can be found by running 
```
cd /opt/community && sudo ansible-playbook community.yml --list-tags 2>&1 | grep "TASK TAGS" | cut -d":" -f2 | awk '{sub(/\[/, "")sub(/\]/, "")}1' | sed -e 's/,//g' | xargs -n 1 | sort -u
```

