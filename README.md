Ansible Role: GoLang Install
=========

Install GoLang.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

        # ===========================================================================
        # Install GoLang
        # ===========================================================================
        - name: Install GoLang
        hosts: servers
        gather_facts: true
        become: false
        tags: play_golang

        roles:
            - { role: ansible-role-golang-install, go_version: 1.20.1 }

License
-------

MIT
