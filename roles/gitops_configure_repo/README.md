GitOps configure Repo
=========

This Role configures a repository and the ssh key to the ArgoCD instance.

Requirements
------------

* ArgoCD/GitOps already configured
* The repository MUST be hosted in Gitlab
* The SSH key has permissions to read from Gitlab repository.

Role Variables
--------------

gitlab_ssh_known_hosts: Should be the ssh known hosts. It is required by ArgoCD when working with a SSH key.

Dependencies
------------

License
-------

GNU GENERAL PUBLIC LICENSE version 3
