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
<!-- readme: contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/saltydk">
            <img src="https://avatars.githubusercontent.com/u/6587950?v=4" width="100;" alt="saltydk"/>
            <br />
            <sub><b>Salty</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/desimaniac">
            <img src="https://avatars.githubusercontent.com/u/5501908?v=4" width="100;" alt="desimaniac"/>
            <br />
            <sub><b>desimaniac</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/owine">
            <img src="https://avatars.githubusercontent.com/u/4283702?v=4" width="100;" alt="owine"/>
            <br />
            <sub><b>owine</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/maximuskowalski">
            <img src="https://avatars.githubusercontent.com/u/13492750?v=4" width="100;" alt="maximuskowalski"/>
            <br />
            <sub><b>Max Kowalski</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Superduper09">
            <img src="https://avatars.githubusercontent.com/u/17391966?v=4" width="100;" alt="Superduper09"/>
            <br />
            <sub><b>Herp</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/chazlarson">
            <img src="https://avatars.githubusercontent.com/u/3865541?v=4" width="100;" alt="chazlarson"/>
            <br />
            <sub><b>Chaz Larson</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/Migz93">
            <img src="https://avatars.githubusercontent.com/u/33037112?v=4" width="100;" alt="Migz93"/>
            <br />
            <sub><b>Migz93</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/BluebonnetSK">
            <img src="https://avatars.githubusercontent.com/u/43162289?v=4" width="100;" alt="BluebonnetSK"/>
            <br />
            <sub><b>BluebonnetSK</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/satzisa">
            <img src="https://avatars.githubusercontent.com/u/54035525?v=4" width="100;" alt="satzisa"/>
            <br />
            <sub><b>Isa</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/RXWatcher">
            <img src="https://avatars.githubusercontent.com/u/14085001?v=4" width="100;" alt="RXWatcher"/>
            <br />
            <sub><b>RXWatcher</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Kalroth">
            <img src="https://avatars.githubusercontent.com/u/6299049?v=4" width="100;" alt="Kalroth"/>
            <br />
            <sub><b>Martin Danielsen</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/TABLE272">
            <img src="https://avatars.githubusercontent.com/u/11992630?v=4" width="100;" alt="TABLE272"/>
            <br />
            <sub><b>TABLE272</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/paris-ci">
            <img src="https://avatars.githubusercontent.com/u/3063324?v=4" width="100;" alt="paris-ci"/>
            <br />
            <sub><b>Arthur</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/FML128">
            <img src="https://avatars.githubusercontent.com/u/33214722?v=4" width="100;" alt="FML128"/>
            <br />
            <sub><b>Merlin Jehli</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Banjer">
            <img src="https://avatars.githubusercontent.com/u/864725?v=4" width="100;" alt="Banjer"/>
            <br />
            <sub><b>Bas</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/grostim">
            <img src="https://avatars.githubusercontent.com/u/3714755?v=4" width="100;" alt="grostim"/>
            <br />
            <sub><b>grostim</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/theotocopulitos">
            <img src="https://avatars.githubusercontent.com/u/1540135?v=4" width="100;" alt="theotocopulitos"/>
            <br />
            <sub><b>theotocopulitos</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/sil3ntc">
            <img src="https://avatars.githubusercontent.com/u/55059643?v=4" width="100;" alt="sil3ntc"/>
            <br />
            <sub><b>Sil3nt</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/fringillidaes">
            <img src="https://avatars.githubusercontent.com/u/57169808?v=4" width="100;" alt="fringillidaes"/>
            <br />
            <sub><b>Finch</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/atilling">
            <img src="https://avatars.githubusercontent.com/u/1081300?v=4" width="100;" alt="atilling"/>
            <br />
            <sub><b>Andrew Tillinghast</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/JackDallas">
            <img src="https://avatars.githubusercontent.com/u/3620144?v=4" width="100;" alt="JackDallas"/>
            <br />
            <sub><b>Dallas</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/stijnthurkow">
            <img src="https://avatars.githubusercontent.com/u/22298631?v=4" width="100;" alt="stijnthurkow"/>
            <br />
            <sub><b>Stijn</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/fuller882">
            <img src="https://avatars.githubusercontent.com/u/43045024?v=4" width="100;" alt="fuller882"/>
            <br />
            <sub><b>fuller882</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Thomvh">
            <img src="https://avatars.githubusercontent.com/u/1483055?v=4" width="100;" alt="Thomvh"/>
            <br />
            <sub><b>Thomvh</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/BeansIsFat">
            <img src="https://avatars.githubusercontent.com/u/24848012?v=4" width="100;" alt="BeansIsFat"/>
            <br />
            <sub><b>BeansIsFat</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/giosann">
            <img src="https://avatars.githubusercontent.com/u/10052873?v=4" width="100;" alt="giosann"/>
            <br />
            <sub><b>Giorgio</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/javi11">
            <img src="https://avatars.githubusercontent.com/u/3855051?v=4" width="100;" alt="javi11"/>
            <br />
            <sub><b>Javier Blanco</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/RyanRadly">
            <img src="https://avatars.githubusercontent.com/u/1883477?v=4" width="100;" alt="RyanRadly"/>
            <br />
            <sub><b>RyanRadly</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/addbee">
            <img src="https://avatars.githubusercontent.com/u/4490516?v=4" width="100;" alt="addbee"/>
            <br />
            <sub><b>Adbe</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/astrodad">
            <img src="https://avatars.githubusercontent.com/u/1663239?v=4" width="100;" alt="astrodad"/>
            <br />
            <sub><b>astrodad</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: contributors -end -->
