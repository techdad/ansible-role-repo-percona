# Ansible Role: Percona Yum Repo

Installation of the official [Percona Yum Repository](https://www.percona.com/doc/percona-server/5.7/installation/yum_repo.html) for CentOS/RHEL 6.x and 7.x systems.

Loosely based on the similar [Remi Repo](https://galaxy.ansible.com/geerlingguy/repo-remi/) role by '[geerlingguy](https://github.com/geerlingguy)'.

Role Variables
--------------

`percona_repo_version: "0.1.4"`

The releaase to the repo. (Not of Percona Server). This should be the only varaible that may need incrementing.

`percona_repo_url: "http://www.percona.com/downloads/percona-release/redhat/{{percona_repo_version}}/percona-release-{{percona_repo_version}}.noarch.rpm"`

The URL to get the repo RPM from.

`percona_repo_gpg_key_url: "https://www.percona.com/downloads/percona-release/RPM-GPG-KEY-percona"`

The Percona RPM GPG key to import.

License
-------

MIT
