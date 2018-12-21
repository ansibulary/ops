(WIP) Ansible Operations Root
=============================

Experimental Ansible framework - this is currently a sandbox for leveraging Ansible in creative ways, to build a self-managing Ansible environment, and to challenge convention with discovery of best practices for more dynamic, general-purpose, and integrated Ansible orchestrations.

This is a parent repo of curated submodules.  This allows a decoupling and independent development of public roles & playbooks with private inventory/vars repositories.

Always perform a recursive clone and set the inventory remote to your own.


_submodule manifest:_

| role | state |
|------|-------|
| os/arch/install | 0.1a |
| os/common/time | 0.1 |
| os/common/locale | 0.1 |
| os/common/hostname | 0.1 |
| os/common/user | 0.2 |
| util/collect | 0.2 |

| playbook | state |
|----------|-------|
| arch | 0.1a |
| _arch_bootstrap | 0.1a |


Copyright (C) 2018 Josiah England - All Rights Reserved

Distributed under the GNU General Public License v3.0

See `COPYING` for full text.
