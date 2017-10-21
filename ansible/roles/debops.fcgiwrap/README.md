## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) fcgiwrap

[![Travis CI](http://img.shields.io/travis/debops/ansible-fcgiwrap.svg?style=flat)](http://travis-ci.org/debops/ansible-fcgiwrap) [![test-suite](http://img.shields.io/badge/test--suite-ansible--fcgiwrap-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-fcgiwrap/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.fcgiwrap-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/4922)

[fcgiwrap](https://github.com/gnosek/fcgiwrap) is a lightweight FastCGI
server which can be set up behind `nginx` server to run CGI applications.
This role allows you to setup separate instances of `fcgiwrap` on different
user accounts, each one accessible through its own UNIX socket.

### Installation

This role requires at least Ansible `v1.8.0`. To install it, run:

    ansible-galaxy install debops.fcgiwrap

### Documentation

More information about `debops.fcgiwrap` can be found in the
[official debops.fcgiwrap documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-fcgiwrap/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`fcgiwrap` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).